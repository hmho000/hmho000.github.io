## web商品网页制作（整体）

_2024年11月15日web网格制作实践_

> 预览网页→[https://hmho000.github.io/web-learning/1115web2.html](https://hmho000.github.io/web-learning/1115web2.html)

<details>
<summary>代码展示（史山）</summary>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>2024-11-15 web作业</title>
        <style>
            .center{
                display: flex; 
                justify-content: center; 
                align-items: center;
                margin: 10px;
            }
            .main{
                display: flex;
            }
            .one{
                height: 200px;
                width:200px;
                background-color: red;
                float: left;
            }
            .two{
                height: 200px;
                width: 700px;
                background-color: #1bd8fa;
                margin-left: 20px;
                float: right;
            }
            .color{
                background-color: green;
                height: 80px;
                width: 140px;
                margin-left: 10%;
                margin-top: 13px;
                /*float: left;*/
            }
            .color-text{
                text-align: center;
                font-size: 25px
            }
            .main1{
                width: 80%;
                margin: auto;
                margin-bottom: 10px;
                display: flex;
            }
            .top{
                height: 90px;
                width: 100%;
                background-color: aqua;
                /* margin-bottom: 0 auto; */
                margin-bottom: 10px;
                display: flex;
            }
            .top-1{
                height: 90px;
                width: 80%;
                background-color: black;
                margin: 0 auto;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .middle{
                height: 90px;
                background-color: yellow;
            }
            .ad{
                height: 270px;
                /* background-color: aqua; */

            }
            .ad-1{
                background-color: tomato;
                height: 270px;
                width: 25%;
                /*margin-bottom: 0 auto;*/
                float: left;
            }
            .ad-2{
                background-color: green;
                height: 270px;
                width: 25%;
                /* margin-bottom: 10px; */
                float: left;
            }
            .ad-3{
                background-color: burlywood;
                height: 270px;
                width: 25%;
                float: left;
            }
            .ad-4{
                background-color: darkorchid;
                height: 270px;
                width:25%;
                float: left;
            }
            .ad-text{
                font-size: 60px;
                width: 100%;
                line-height: 250%;
                text-align: center;
            }
            .end{
                background-color: aqua;
                height: 90px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .end-2{
                background-color: rgb(0, 255, 255);
                height:110px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .top-title-text{
                font-size: 40px;
                color: rgb(255, 255, 255);
            }
            .title2{
                font-size: 40px;
                align-items: center;
                justify-content: center;
            }
            .kj{
                display: flex;
                float: right;
                height:auto;
                width: auto;
                background-color: peru;
                font-size: 20px;
                align-items: center;
                justify-content: center;
                margin-top: 70px;
            }
        </style>
    </head>
    <body>
    <div class="top">
        <div class="top-1"><p class="top-title-text">主标题</p></div>
    </div>
    <div class="middle main1 title2"><p>副标题</p></div>
    <div class="ad main1">
        <div class="ad-1"><p class="ad-text">广1</p></div>
        <div class="ad-2"><p class="ad-text">广2</p></div>
        <div class="ad-3"><p class="ad-text">广3</p></div>
        <div class="ad-4"><p class="ad-text">广4</p></div>
    </div>
    <div class="end"><p style="font-size: 40px">分隔栏1</p></div>
    <div class="center">
        <div class="main">
            <div class="one"><p style="text-align: center;font-size: 60px" >工具栏</p></div>
            <div class="two">
                <div class="main">
                    <div class="color"><p class="color-text">版块1</p></div>
                    <div class="color"><p class="color-text">版块2</p></div>
                    <div class="color"><p class="color-text">版块3</p></div>
                </div>
                <div class="main">
                    <div class="color"><p class="color-text">版块4</p></div>
                    <div class="color"><p class="color-text">版块5</p></div>
                    <div class="color"><p class="color-text">版块6</p></div>
                </div>
            </div>
        </div>
    </div>
    <div class="end-2"><p style="font-size: 40px">分隔栏2</p></div>
    <div class="kj">kj制作 2024年11月15日 14:07:44</div>
    </body>
</html>

```

</details>

## web商品页面小米su7（结合图片）

_2024年11月20日web网格与图片练习_

> 预览网页→[https://hmho000.github.io/web-learning/1120web21](https://hmho000.github.io/web-learning/1120web21.html)

<details>
<summary>代码展示</summary>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>2024-11-20 web作业</title>
        <style>
            .center{
                display: flex; 
                justify-content: center; 
                align-items: center;
                margin: 10px;
            }
            .main{
                display: flex;
            }
            .one{
                height: 200px;
                width:200px;
                background-color: red;
                float: left;
            }
            .two{
                height: 200px;
                width: 700px;
                background-color: #1bd8fa;
                margin-left: 20px;
                float: right;
            }
            .color{
                background-color: green;
                height: 80px;
                width: 140px;
                margin-left: 10%;
                margin-top: 13px;
                /*float: left;*/
            }
            .color-text{
                text-align: center;
                font-size: 25px
            }
            .main1{
                width: 80%;
                margin: auto;
                margin-bottom: 10px;
                display: flex;
            }
            .top{
                height: 90px;
                width: 100%;
                background-color: aqua;
                /* margin-bottom: 0 auto; */
                margin-bottom: 10px;
                display: flex;
            }
            .top-1{
                height: 90px;
                width: 80%;
                background-color: black;
                margin: 0 auto;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .middle{
                height: auto;
                background-color: yellow;
            }
            .ad{
                height: 270px;
                /* background-color: aqua; */

            }
            .ad-1{
                background-color: tomato;
                height: 270px;
                width: 25%;
                /*margin-bottom: 0 auto;*/
                float: left;
            }
            .ad-2{
                background-color: green;
                height: 270px;
                width: 25%;
                /* margin-bottom: 10px; */
                float: left;
            }
            .ad-3{
                background-color: burlywood;
                height: 270px;
                width: 25%;
                float: left;
            }
            .ad-4{
                background-color: darkorchid;
                height: 270px;
                width:25%;
                float: left;
            }
            .ad-text{
                font-size: 60px;
                width: 100%;
                line-height: 250%;
                text-align: center;
            }
            .end{
                background-color: aqua;
                height: 90px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .end-2{
                background-color: rgb(0, 255, 255);
                height:110px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .top-title-text{
                font-size: 40px;
                color: rgb(255, 255, 255);
            }
            .title2{
                font-size: 40px;
                align-items: center;
                justify-content: center;
            }
            .img{
                height: 270px;
                width: auto;
                width: 100%;
            }
         
        </style>
    </head>
    <body>
    <div class="top">
        <div class="top-1"><p class="top-title-text">小米su7</p></div>
    </div>
    <div class="middle main1 title2"><img  src="https://img.pcauto.com.cn/images/upload/upc/tx/auto5/2312/28/c26/399344622_1703756564287_1024.jpg" alt="小米su7"></div>
    <div class="ad main1">
        <div class="ad-1"><img class="img" src="https://ts1.cn.mm.bing.net/th/id/R-C.c7db6f01850d3c707a7785067073b663?rik=CAXkhM1ISyJrcw&riu=http%3a%2f%2fimg4.pcauto.com.cn%2fpcauto%2fimages%2ftpyh%2f20240118%2f17225002.jpg&ehk=tr54le0fbf%2fHHr3JaIyuvruCKbO9rWWFRtLu%2byFGHiY%3d&risl=&pid=ImgRaw&r=0" alt="su7"></div>
        <div class="ad-2"><img class="img" src="https://image.bitautoimg.com/appimage-2400-w1/mapi/news/2023/11/15/b1eed06e3b024b96b873a0901bcb5898.jpg" alt=""></div>
        <div class="ad-3"><img class="img" src="https://img2.bitautoimg.com/autoalbum/files/20231228/579/202312282490376259157948204_3000x2000_w1.jpg" alt=""></div>
        <div class="ad-4"><img class="img" src="https://k.sinaimg.cn/n/sinakd20240410s/200/w1080h720/20240410/f247-56527a15810a2de992fc7752f14daa89.jpg/w700d1q75cms.jpg?by=cms_fixed_width" alt=""></div>
    </div>
    <div class="end"><p style="font-size: 40px">2024年11月20日 kj制作</p></div>
   
    </body>
</html>

```
</details>

## web商品网页网格练习（图片、文字版）

_2024年11月22日web网格图片文字结合练习_

> 预览网页→[https://hmho000.github.io/web-learning/1122web22.html](https://hmho000.github.io/web-learning/1122web22.html)

<details>
<summary>代码展示</summary>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>网页_网格部分</title>
    <style>
        .one{
            width: 80%;
            height: 250px;
            background-color: blanchedalmond;
            display: grid;
            grid-template-columns: repeat(5,1fr);
            grid-template-rows: repeat(2,120px);
            grid-gap: 10px 10px;
            margin: 0 auto;
        }
        .two{
            height: 120px;
            border: 0.5px solid black;
            text-align: center;
        }
        .two:nth-child(1){
            background-color: rgb(245, 223, 99);
            width: 100%;
            height: 100%;
            grid-row-start: 1;
            grid-row-end: 3;
        }
        .img1{
            height: 250px;
            width: 100%;
        }
        .img2{
            height: 65%;
        }
        .text{
            font-size: 25px;
            margin-top: 0px;
        }
        
    </style>
</head>
<body>
<div class="one">
    <div class="two"><img class="img1" src="https://x0.ifengimg.com/res/2020/7C41AA2478E4CCB101266B9FA0AD0D3A13CEC615_size214_w1200_h1083.jpeg" alt=""></div>
    <div class="two"><img class="img2" src="https://tse4-mm.cn.bing.net/th/id/OIP-C.wausC-Zs3W96ho1j8t7k_wHaHa?rs=1&pid=ImgDetMain" alt=""><p class="text">手机1</p></div>
    <div class="two"><img class="img2" src="https://img1.wushang.com/pn/wsec-img1/2021/4/26/3a757431-d78b-4b79-939b-41f458bd4148.jpg?x-oss-process=image/resize,w_800,h_800" alt=""><p class="text">手机2</p></div>
    <div class="two"><img class="img2" src="https://www.ha.10086.cn/v1/tfs/T1OWdTBydT1R4cSCrK.png" alt=""><p class="text">手机3</p></div>
    <div class="two"><img class="img2" src="https://image5.suning.cn/uimg/b2c/newcatentries/0000000000-000000000600037346_1_800x800.jpg" alt=""><p class="text">手机4</p></div>
    <div class="two"><img class="img2" src="https://ts1.cn.mm.bing.net/th/id/R-C.dc15217a3f940a4d63deec7ca19c381c?rik=Y1%2bfXeRZJuTPSg&riu=http%3a%2f%2fimg03.mifile.cn%2fwebfile%2fimages%2fopen%2fwww%2f2014102801%2fmi3.jpg&ehk=OfrPlxzpL6bZuA1V4o8jvtSBNkCruG3cL3QTxaqkIc4%3d&risl=&pid=ImgRaw&r=0" alt=""><p class="text">手机5</p></div>
    <div class="two"><img class="img2" src="https://n.sinaimg.cn/sinakd20200803ac/400/w1200h800/20200803/7fc3-ixeeirz8562997.jpg" alt=""><p class="text">手机6</p></div>
    <div class="two"><img class="img2" src="https://gfs17.gomein.net.cn/T1EMbIBKCT1RCvBVdK_800.jpg" alt=""><p class="text">手机7</p></div>
    <div class="two"><img class="img2" src="https://tse4-mm.cn.bing.net/th/id/OIP-C.SS9FNnhV2ICbsNlbOv4r6wHaHa?rs=1&pid=ImgDetMain" alt=""><p class="text">手机8</p></div>
</div>
</body>
</html>

```
</details>


- 于2024年11月26日 22:03:25由kj更新






