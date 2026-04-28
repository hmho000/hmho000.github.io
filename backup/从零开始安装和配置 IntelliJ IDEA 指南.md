# 从零开始安装和配置 IntelliJ IDEA 指南

## 第一步：安装 Java 环境 (JDK)

IntelliJ IDEA 是用来编写 Java 程序的主要工具之一，但它本身不包含 Java 运行环境。所以我们需要先安装 **JDK**。

### 1. 下载 JDK

1. 访问 Oracle 官方网站的 JDK 下载页面：
 [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
2. 选择最新的 **LTS** 版本（目前推荐 **JDK 21** ）。LTS 版本更稳定，支持时间更长。
![下载jdk21](https://ooo.0x0.ooo/2025/09/08/OlKyyt.md.png)
4. 根据你的操作系统选择正确的安装包： 
*Windows*: 
 * 下载 `x64 Installer` 版本（文件名为 `jdk-21_windows-x64_bin.exe` 类似）
*macOS*:
 * **Intel 芯片**：下载 `x64 DMG Installer`
 * **Apple Silicon 芯片 (M1/M2/M3)**：下载 `AArch64 DMG Installer`
 * （对于新手，安装器 `.exe` 或 `.dmg` 是最简单的选择）

### 2. 安装 JDK

*Windows* :

 1. 双击下载好的 `.exe` 文件。
 2. 出现安装向导，点击“下一步”。
 ![安装jdk](https://ooo.0x0.ooo/2025/09/08/OlKFyB.md.png)
 4. 可以默认安装路径（通常是 `C:\Program Files\Java\jdk-21\`），也可以更改。**记住这个路径，后面要用！**
 5. 继续点击“下一步”，直到安装完成。
 
*macOS*:

 1. 双击下载好的 `.dmg` 文件。
 2. 打开后，双击包中的 `.pkg` 图标。
 3. 根据安装向导的提示，一路点击“继续”，同意许可协议，并输入你的电脑密码完成安装。
 4. JDK 会自动安装到标准目录（`/Library/Java/JavaVirtualMachines/`），无需手动设置路径。

### 3. 验证 JDK 是否安装成功

* **Windows**:
 1. 按下键盘上的 `Win + R` 键，输入 `cmd`，然后按回车，打开命令提示符。
 2. 输入命令 `java -version` 并按回车。
 3. 如果显示类似下面的版本信息（版本号和你下载的一致），说明安装成功。
 ```
 java version "21.0.2" 2024-01-16 LTS
 Java(TM) SE Runtime Environment (build 21.0.2+13-LTS-58)
 Java HotSpot(TM) 64-Bit Server VM (build 21.0.2+13-LTS-58, mixed mode, sharing)
 ```
* **macOS**:
 1. 打开“启动台” -> “其他” -> “终端”。
 2. 输入命令 `java -version` 并按回车。
 3. 同样检查版本信息是否正确。

---

## 第二步：下载并安装 IntelliJ IDEA

### 1. 选择版本

IntelliJ IDEA 有两个版本：
* **Ultimate (旗舰版)**：功能全面，支持各种语言和框架（如 Spring, Python, JavaScript），但**收费**（对学生免费）。
* **Community (社区版)**：免费，功能足够用于学习 **Java** 和 Android 开发。

**作为新手，咱们先下载免费的 Community 版本。**

### 2. 下载安装

1. 访问 JetBrains 官网下载页：
 [https://www.jetbrains.com/zh-cn/idea/download/](https://www.jetbrains.com/zh-cn/idea/download/)
2. 向下滑在“Community”栏目下，点击你的操作系统（Windows, macOS, Linux）对应的 **下载** 按钮。
![安装ide](https://ooo.0x0.ooo/2025/09/08/OlKvUX.md.png)
4. 下载完成后，运行安装程序。 * **Windows**:
 * 双击安装程序 `.exe`。
 ![安装ide](https://ooo.0x0.ooo/2025/09/08/OlK1ea.md.png)
 * 选择安装路径（默认会安装到C盘，我这边选择的D）。
 ![选择安装目录](https://ooo.0x0.ooo/2025/09/08/OlKpaj.md.png)
 * 在安装选项界面，勾选如图选项：
 ![配置项](https://ooo.0x0.ooo/2025/09/08/OlKhds.md.png)
 * `64-bit launcher` (创建桌面快捷方式)
 * `Add "Open Folder as Project"` (增加右键菜单)
 * `.java` (关联 Java 文件)
 * 点击“下一步（Next）”直到安装完成，最后点击“完成（Finish）”。
 ![等待ide安装](https://ooo.0x0.ooo/2025/09/08/OlKKji.md.png)
 * **macOS**:
 * 双击下载的 `.dmg` 文件。
 * 将 IntelliJ IDEA CE 的图标拖拽到 `Applications` 文件夹中即可完成安装。

---

## 第三步：首次运行与基本配置

### 1. 启动 IDEA

* **Windows**: 从开始菜单或桌面快捷方式启动。
* **macOS**: 在“应用程序”中找到并启动它。

首次运行会进行一些初始化配置。

### 2. 重要初始设置

1. **是否导入设置**：第一次启动会问你是否导入之前的设置，选择 `跳过导入（Do not import settings）`（不导入设置，使用默认配置）。
![导入配置](https://ooo.0x0.ooo/2025/09/08/OlKARL.md.png)
3. **接受用户协议**：勾选同意，然后点击“Continue”。
4. **数据分享**：是否发送使用数据给 JetBrains 以帮助他们改进产品，可以选择“Don't Send”不发送。
5. **UI 主题选择**：选择你喜欢的主题，比如 `Light` (浅色) 或 `Dark` (深色)。之后可以随时更改。
6. **插件安装**：初始界面会推荐一些插件，作为新手可以先直接点击“Skip Remaining and Set Defaults”（跳过其余并设置默认），后续有需要再安装。
7. **激活**：社区版不需要激活，直接点击“Start trial”或“Start using IDEA”即可开始使用。
### 3. 配置 JDK（关键步骤！！！）

现在我们要告诉 IntelliJ IDEA 我们刚才安装的 JDK 在哪里。

1. 在欢迎界面，点击左侧的 `项目（Projects）` 。
2. 右侧选择 `新建项目（New Project）`。
![创建新项目](https://ooo.0x0.ooo/2025/09/08/OlKgsx.md.png)
3. 在页面中部 **“JDK”** 旁边，点击下拉菜单。
 * **如果这里自动检测到了你安装的 JDK 21**（例如显示 `21`），那么太好了，你可以直接下一步。
 * **如果没有检测到**，点击 `从磁盘中添加JDK...（Add JDK...）`。

> 3.1. 在弹出的文件选择窗口中，找到你安装 JDK 的路径：
> * **Windows**: 通常是在 `C:\Program Files\Java\` 下，选择你安装的 `jdk-21` 这个文件夹。
>  * **macOS**: 路径是 `/Library/Java/JavaVirtualMachines/jdk-21.jdk/Contents/Home`（请将 `21` 替换为你下载的实际版本号）。

4. 选择好 JDK 路径后，点击 `创建`。此时 IDEA 就配置好了 Java 环境。
5. 项目名称（`Name`）可以取一个简单的，比如 `HelloWorld`。
6. 点击 `创建` 按钮，你的第一个项目就创建成功了！
![选择jdk](https://ooo.0x0.ooo/2025/09/08/OlKrFC.md.png)

---

## 第四步：创建并运行你的第一个程序

现在你进入了 IDEA 的主界面。

1. **创建Java类**：
 * 在左侧的项目结构栏（称为“项目工具窗口”），找到 `src` 文件夹。
 * 右键点击 `src` -> `新建（New）` -> `Java类（Java Class）`。
  ![创建JAVA类](https://ooo.0x0.ooo/2025/09/08/OlK7ES.md.png)
 * 输入类名，例如 `Main`，按回车。
 ![类名](https://ooo.0x0.ooo/2025/09/08/OlKNIN.md.png)

2. **编写代码**：
 * IDEA 会自动生成类结构。我们写入一个经典的入门程序：
 ```java
 public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World! 我终于成功啦！");
    }
}
 ```

3. **运行程序**：
 * 你会看到代码编辑器顶部区域，`当前文件` 字样的旁边有一个小小的 **绿色三角** ▶️ 图标。
 * 点击这个绿色三角。
 * 或者，直接在代码编辑器内右键，选择 `Run 'Main.main()'`。

4. **查看结果**：
 * 程序运行后，IDE 底部会弹出一个 **“Run”** 工具窗口。
 * 里面会显示程序的输出：`Hello, World! 我终于成功啦！`
 ![成功运行](https://ooo.0x0.ooo/2025/09/08/OlKJep.md.png)

恭喜你！你已经成功完成了从安装到运行的全部步骤！🎉

## 总结与后续建议

| 步骤 | 内容 | 关键点 |
| :--- | :--- | :--- |
| **1** | **安装 JDK** | 去 Oracle 官网下载，并验证 `java -version` |
| **2** | **安装 IDEA** | 下载 **Community (社区版)**，按向导安装 |
| **3** | **配置环境** | 首次创建项目时，通过 `Add JDK...` 指定 JDK 安装路径 |
| **4** | **创建运行** | 在 `src` 下新建 Java Class，写代码，点击绿色三角运行 |

* **不要怕出错**：编程过程中会遇到无数错误，这是学习过程的必经之路。学会阅读错误信息（通常是红色的）是最重要的技能之一。
* **善用搜索**：任何问题，都可以尝试将错误信息复制到百度或 Bing 中搜索，很大概率已经有人遇到过同样的问题并提供了解决方案。
* **熟悉界面**：多点点看 IDEA 的各个菜单，了解一下各个窗口（如 Project, Run, Terminal）是干什么的。

## Q&A

---

### Q：为什么“不用去配置系统的环境变量”？

> A：因为 IntelliJ IDEA 是一个高度集成的开发环境，它在**自己内部**已经管理了你为项目指定的 JDK。当你按照上一步教程，在创建新项目时通过 > `Add JDK...` 告诉了 IDEA JDK 的安装路径后，IDEA 就知道去哪里找编译器 (`javac`) 和运行时 (`java`) 来编译和运行你的代码了。
> 
> 所以，**仅仅在 IDEA 里写代码、点绿色三角运行程序，不配置系统环境变量是完全没问题的。**

---

### Q：为什么“强烈建议”配置环境变量？

> A：因为配置系统环境变量 `JAVA_HOME` 和 `PATH` 是为了让**整个操作系统**而不仅仅是 IDEA 知道 Java 的存在。这会在很多场景下带来便利：
> 
> 1. **在命令行（终端/CMD）中使用 Java**：
>  * 你想在 IDEA 自带的终端或者系统自带的 `cmd` 或 `PowerShell` 中直接输入 `java -version`、`javac` 等命令时，系统需要知道去哪里找这些命令。
>  * **未来你一定会用到**，比如使用 `Maven`、`Gradle` 等构建工具，它们通常依赖于 `JAVA_HOME` 这个环境变量来定位 JDK。
> 
> 2. **其他开发工具**：
>  * 很多其他软件（比如服务器软件 Tomcat、构建工具 Gradle 等）在启动时都会查找 `JAVA_HOME` 环境变量来确定使用哪个 Java 环境。
> 
> 3. **避免未来 confusion**：
>  * 提前配置好是一劳永逸的事情，可以避免未来某个时候突然出现“命令找不到”的错误而不知所措。

---

## 如何配置系统环境变量 (详细步骤)

下面为你提供 Windows 和 macOS 的详细配置方法。

### 🔧 对于 Windows 系统

1. **确认 JDK 安装路径**：
 * 通常路径是 `C:\Program Files\Java\jdk-21` (请将 `21` 替换为你安装的实际版本号)。
 * **非常重要**：请打开文件资源管理器确认这个路径存在。路径中应该包含 `bin`, `lib` 等文件夹。

2. **打开环境变量设置**：
 * 在开始菜单搜索 **“编辑系统环境变量”** 并打开。
 * 或者按 `Win + R`，输入 `sysdm.cpl` 回车，然后选择“高级”选项卡，点击“环境变量”按钮。

3. **新建 `JAVA_HOME` 变量** (系统变量)：
 * 在下面的“系统变量”区域，点击 **“新建...”**。
 * **变量名**： `JAVA_HOME`
 * **变量值**：你的 JDK 安装路径，例如 `C:\Program Files\Java\jdk-21`
 * 点击“确定”。



4. **修改 `Path` 变量**：
 * 在“系统变量”区域，找到并选中 `Path` 变量，点击 **“编辑...”**。
 * 点击 **“新建”**，然后添加一条新记录： `%JAVA_HOME%\bin`
 * **说明**：`%JAVA_HOME%` 会动态引用你上一步设置的路径，`\bin` 是包含所有可执行文件（如 `java`, `javac`）的目录。
 * 点击“确定”保存。



5. **验证配置**：
 * 关闭所有已经打开的命令行窗口，**重新打开一个新的 `cmd` 或 `PowerShell`**。
 * 输入 `java -version`，应该显示你安装的版本号。
 * 输入 `javac -version`，应该显示同样的版本号。
 * 输入 `echo %JAVA_HOME%`，应该显示你设置的路径。
 * 如果这些命令都返回了正确信息，恭喜你，配置成功！



### 🍎 对于 macOS 系统

macOS 在安装 JDK `.dmg` 包时，通常会自动在 `/usr/libexec/java_home` 这个位置创建一个链接，命令行工具已经可以找到 Java。但手动设置 `JAVA_HOME` 仍然是一个好习惯。

1. **打开终端**（Terminal）。
2. **确定 JDK 的安装路径**：
 * 在终端中输入以下命令并回车：
 ```bash
 /usr/libexec/java_home
 ```
 * 它会输出 JDK 的完整安装路径，例如：`/Library/Java/JavaVirtualMachines/jdk-21.jdk/Contents/Home`
 * 复制这个路径。

3. **编辑 shell 配置文件**：
 * macOS 通常使用 `zsh`（新系统）或 `bash`（旧系统）作为默认 shell。
 * 首先判断你用的哪种，在终端输入 `echo $SHELL`：
 * 如果输出 `/bin/zsh` -> 编辑 `~/.zshrc` 文件
 * 如果输出 `/bin/bash` -> 编辑 `~/.bash_profile` 文件
 * （近年来新的 macOS 系统基本都是 `zsh`）

4. **以 `zsh` 为例**，在终端输入以下命令来编辑配置文件：
 ```bash
 nano ~/.zshrc
 ```

5. **添加环境变量**：
 * 在打开的文件末尾（如果之前没有内容，就在空文件中），添加以下两行：
 ```bash
 export JAVA_HOME=$(/usr/libexec/java_home)
 export PATH=$JAVA_HOME/bin:$PATH
 ```
 * **说明**：第一行使用 `$(/usr/libexec/java_home)` 命令自动获取当前 JDK 路径并赋值给 `JAVA_HOME`。第二行将 JDK 的 `bin` 目录添加到 `PATH` 的最前面。

6. **保存并退出**：
 * 按 `Ctrl + O` 回车来保存文件。
 * 按 `Ctrl + X` 退出 nano 编辑器。

7. **使配置生效**：
 * 在终端中输入以下命令，让刚修改的配置立即生效：
 ```bash
 source ~/.zshrc
 ```

8. **验证配置**：
 * 关闭终端再重新打开，或直接在新终端中输入：
 ```bash
 java -version
 javac -version
 echo $JAVA_HOME
 ```
 * 如果所有命令都返回正确信息，则配置成功。

---

### 总结

| 场景 | 是否需要配置环境变量 |
| :--- | :--- |
| **仅使用 IntelliJ IDEA 的图形界面按钮运行程序** | **不需要** |
| **需要在系统命令行中使用 `java`, `javac` 等命令** | **必须** |
| **为了未来使用 Maven、Gradle 等工具做准备** | **必须** |
| **让系统环境更整洁，避免未来可能出现的问题** | **强烈建议** |

**给你的最终建议：** 既然你已经走到了这一步，**花 5 分钟时间把它配置好**，这是一项一次性的投资，能为你的后续开发学习省去很多不必要的麻烦。



现在，你已经搭建好了强大的开发环境，可以开始探索精彩的编程世界了！