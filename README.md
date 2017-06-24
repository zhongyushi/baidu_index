**问题：**
说起前端其实基础的东西就那么多，也不难理解，但是如果想做一个好的页面，还是要做大量的练习，只有通过大量反复的练习，我们才能更加熟悉一些常用标签的使用场景和使用技巧，今天我就给大家提供一个简单的百度首页界面。可以直接复制代码运行。

**效果图如下：**
![](images/screenshot_1498213636065.png)

**代码如下：**

~~~
<html>
<head>
    <title>百度</title>
    <style>
        a{color:#333;font-weight: 700;font-size:13px;}
        /*浮动样式**/
       .f_r{float:right;}
       .clear{clear: both;}
       /*居中样式**/
       .center{
            margin:0 auto;
            text-align: center;
        }
       ul li{
            list-style: none;
            float:left;
            margin-right: 10px;
        }
        /**顶部更多产品样式***/
        .more_products{
            width:60px;
            text-align: center;
            background:#38f;
        }
        .more_products a{
            color: #fff;
        }
        /**搜索框顶部图片***/
        .search_img {
            clear: both;
            text-align: center;
            margin: 0 auto;
        }
        .search_img img{
            height: 160px;
        }
        /*搜索框样式**/
        .search_form {
            text-align: center;
            margin: 0 auto;
            min-height: 200px;
        }
        .search_form input[type="text"]{
            width:500px;
            height:40px;
            font-size:14px;
        }
        .search_form input[type="button"]{
            width:100px;
            height:40px;
            background: #3385FF;
            color:#fff;
            border-bottom: 1px solid #2d78f4;
            -webkit-appearance: none;
            -webkit-border-radius:0;
            outline: medium;
            margin-left:-6px;
        }
        /*底部样式**/
        .footer{
            color:#999;
        }
        
        .friend_link{
            width:400px;
            margin-bottom:20px;
            list-style: none;
            margin:0 auto;
            text-align: center;
            margin-bottom: 15px;
        }
        .friend_link  li a{
            color: #999;
        } 
        .footer .mobile_link{
            color: #666;
            font-size: 14px;
            font-weight: 700;
        }
        .copyright{
            display: block;
            padding-top:20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <ul class="f_r">
        <li><a href="javascript:;">新闻</a></li>
        <li><a href="javascript:;">hao123</a></li>
        <li><a href="javascript:;">地图</a></li>
        <li><a href="javascript:;">视频</a></li>
        <li><a href="javascript:;">贴吧</a></li>
        <li><a href="javascript:;">学术</a></li>
        <li><a href="javascript:;">登录</a></li>
        <li><a href="javascript:;">设置</a></li>
        <li class="more_products"><a href="javascript:;">更多产品</a></li>
    </ul>

    <div class="search_img">
        <img src="https://ss1.bdstatic.com/5eN1bjq8AAUYm2zgoY3K/r/www/cache/yunying/Turing2017PC/common/doodle-2/66.jpg">
    </div>
    <div class="search_form">
        <form>
            <input type="text" name="keyword">
            <input type="button" value="百度一下">
        </form>
    </div>
    <div class="footer center">
        <div>
            <img src="https://ss1.bdstatic.com/5eN1bjq8AAUYm2zgoY3K/r/www/cache/static/protocol/https/home/img/qrcode/zbios_x2_9d645d9.png" width="60px" height="60px">
            <p class="mobile_link">手机百度</p>
        </div>
        <ul class="friend_link">
            <li><a href="javascript:;">把百度设为首页</a></li>
            <li><a href="javascript:;">关于百度</a></li>
            <li><a href="javascript:;">About Baidu</a></li>
            <li><a href="javascript:;">百度推广</a></li>
        </ul>
        <div class="copyright">©2017 Baidu 使用百度前必读 意见反馈 京ICP证030173号  京公网安备11000002000001号 </div>
    </div>
</body>
</html>
~~~

附上git地址：https://github.com/zhongyushi/baidu_index
总结：如果您对我的代码优化有更好的建议，欢迎交流指正。
