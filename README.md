  <div>
    <a href="https://github.com/Justin1107-good/">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=console.log(%22Hello%2C%20World%22); 1024!1024!1024!1024!1024!1024! &center=true&size=27" />
    </a>
  </div>

 <style>
   

* {
    margin: 0;
    padding: 0;
    font-family: "Lantinghei SC", "Microsoft Yahei", 宋体, Arial, Helvetica, sans-serif;
    font-size: 12px;
    font-style: normal;
}
#mian {
    display: none;
}
/*背景设置*/
body {
    font-family: arial, sans-serif;
    background-image: linear-gradient(125deg, #2c3e50, #27ae60, #2980b9, #e74c3c, #8e44ad);;
    background-size: 100%;
    animation: bganimation 15s infinite;
}
@keyframes bganimation {
0% {
background-position: 0% 50%;
}
50% {
background-position: 100% 50%;
}
100% {
background-position: 0% 50%;
}
}
/*导航栏*/
#header {
    height: 31;
    min-width: 100%;
    width: 100%;
    padding: 9px 10px 0 0;
    position: relative;
}
#hd_nav {
    float: center;
}
ul {
    list-style: none;
}
#hd_nav li {
    border-right: 1px solid rgba(225, 225, 225, 0.2);
    float: left;
    height: 14px;
    padding: 0 10px;
}
a {
    text-decoration: none;
    cursor: pointer;
}
#hd_nav .skin a {
    padding-left: 22px;
    position: relative;
}
#hd_nav a {
    color: #fff;
    height: 20px;
    line-height: 14px;
}
 
.a1 {
    margin-left: 55px; 
	font-size:55px;
	text-align:center;
	 font-family: seamless
} 
.a2{ 
     margin-left: 55px;  
	 font-size:25px;
	 text-align:center; 
}
 .a3{ 
     margin-left: 55px;  
	 font-size:20px;
	 text-align:center; 
	 font-style:color below
}
/*版权声明*/
#footer {
    width: 100%;
    height: 68px;
    float: inherit;
    line-height: 26px;
    color: #fff;
    text-align: center;
    padding-top: 50%;
}
/*设置第一次显示的画面*/
#hello h1 {
    font-size: 300px;
    text-transform: uppercase;
    font-weight: 900;
    letter-spacing: 10px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    margin: 0;
    background-image: linear-gradient(125deg, #2c3e50, #27ae60, #2980b9, #e74c3c, #8e44ad);
    background-size: cover;
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
}
#mian {
    font-size: 500px;
    text-transform: uppercase;
    font-weight: 900;
    letter-spacing: 10px;
    position: absolute;
    top: 50%;
    left: 60%;
    transform: translate(-50%, -50%);
    margin: 0;
    background-image: linear-gradient(125deg, #2c3e50, #27ae60);
    background-size: cover;
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
}
</style>
 <meta charset="utf-8" /> 
<title>欢迎到来</title>
<div id="hello"> 
  <h1>HELLO</h1>
</div>
    
    
<div id="mian">  
      <ul>  
        <li>
		<a class="a1" href="./Default.aspx"> 进入 </a> 
		</li>
		<li>
		 <label class="a2">搭建本地化NuGet，无需操作直接拿来使用
		 <br/>
		 只需修改简单的配置即可
		 <br/> 
		 </label>
		</li>
		<li><br/> <br/> <br/> <a class="a3" href="./code.html">配置文件下载</a></li>
      </ul>
   
  <div id="footer">
    <p>Copyright © 2020-2023 Justin Wang'vlog, All rights reserved.<br />
      2020-2023，版权所有 Justin Wang</p>
  </div>
</div>




<script>
//开启界面时调用
window.onload = function () { 
  if (window.name == "") {
/*    alert("首次进入");*/
    window.setTimeout("init();", 2000);
    window.name = "isReload"; // 在首次进入页面时我们可以给window.name设置一个固定值 
  } else if (window.name == "isReload") {
    /*alert("页面刷新");*/
    //让整体界面显示出来
    var test = document.getElementById("mian");
    test.setAttribute("style", "display: inline;");
    //隐藏欢迎界面    
    var text = document.getElementById("hello");
    text.setAttribute("style", "display: none;");
  }


}


function init() {
  //让整体界面显示出来
  var test = document.getElementById("mian");
  test.setAttribute("style", "display: inline;");
  //隐藏欢迎界面    
  var text = document.getElementById("hello");
  text.setAttribute("style", "display: none;");
}

</script>





