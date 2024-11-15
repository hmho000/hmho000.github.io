<h1>2024年11月15日web实践</h1>
→→→→→→[网页预览](https://hmho000.github.io/web-learning/index.html)
```
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