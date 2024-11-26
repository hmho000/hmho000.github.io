## web商品网页制作

_2024年11月15日web网格制作实践_

> 预览网页→[hmho000.github.io/web-learning/1115web2.html](https://hmho000.github.io/web-learning/1115web2.html)

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

### 计数<!-- ##{"script":"<script src='https://blog.meekdai.com/Gmeek/plugins/GmeekBSZ.js'></script>"}## -->






