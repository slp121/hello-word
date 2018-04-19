<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>新增属性</title>
     <SCRIPT language="javascript">
       <!--
        var sound1="资源/音乐/Alessia Cara - How Far I'll Go.mp3"
        var sound2="资源/音乐/Deutschland Sucht Den Superstar - Cry On My Shoulder.mp3"
        var sound3="资源/音乐/John The Whistler - Wild Wild Web.mp3"
        var sound4="资源/音乐/Justin Bieber - Sorry.mp3"
        var sound5="资源/音乐/Maroon 5、Future - Cold.mp3"
        var sound6="资源/音乐/SING女团 - 极乐净土.mp3"
        var sound7="资源/音乐/冯曦妤 - 我在那一角落患过伤风.mp3"
        var sound8="资源/音乐/葛林 - 林中鸟.mp3"
        var sound9="资源/音乐/鹏泊 - 啷个哩个啷.mp3"
        var sound10="资源/音乐/洛天依 - 山外小楼夜听雨.mp3"
        var x=Math.round(Math.random()*9)
        if (x==0) x=sound1
        else if (x==1) x=sound2
        else if (x==2) x=sound3
        else if (x==3) x=sound4
        else if (x==4) x=sound5
        else if (x==5) x=sound6
        else if (x==6) x=sound7
        else if (x==7) x=sound8
        else if (x==8) x=sound9
        else x=sound10
        if (navigator.appName=="Microsoft Internet Explorer")
        document.write('<bgsound src='+'"'+x+'"'+' loop="infinite">')
        else
        document.write('<embed src='+'"'+x+'"'+'hidden="true" border="0" width="10" height="10" loop="true">')
        //-->
      </SCRIPT>
    
    
	<style type="text/css">
	body{
		background:url(资源/images/200906.jpg) no-repeat fixed center;
	}
	   @keyframes example {
          0%   {right:50px; bottom:50px;}
          25%  {right:100px; bottom:50px;}
          50%  {right:100px; bottom:100px;}
          75%  {right:50px; bottom:100px;}
          100% {right:50px; bottom:50px;}
      }
      .box{
          width: 150px;
          height: 150px;
          background:url(资源/images/微信.jpg);
          background-size:cover;
          float:right;
          border-radius: 10px;
          box-shadow:1px 1px 1px 0031;
          position:relative;
          position:fixed;
          animation:example 4s 2s infinite alternate;
      }
      .text{
          width:150px;
          height:20px;
          font-size:15px;
          color:#cc00ff;
          background:rgba(255,255,255,0.1);
          text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
          bottom:0;
          position:absolute;
          text-align:center;
          text-indent: 1em;
          border-bottom-right-radius:10px;
		  border-bottom-left-radius:10px;
      }    
			 
	video{
		width:500px;
		height: auto;
		background: url(资源/images/1533.jpg);
		background-size: auto;
		margin:10px auto;
	}
	audio{
		width:200px;
		height:200px;
		float: left;
		background: url(资源/images/1533.jpg);
		background-size: 200px 200px;
	}
	</style>
</head>
<body>
  <!--背景音乐
 <audio controls="controls" hidden="hidden" autoplay="autoplay" loop="loop">
  <source src="资源/音乐/Deutschland Sucht Den Superstar - Cry On My Shoulder.mp3">
 </audio>-->
 

  <div class="box">
   <div class="text"><marquee direction="right" behavior="alternate" loop="-1" scrollamount="2">扫一扫有惊喜！</marquee></div>
  </div>


    <form action="XX.php">
    <table width="800" border="0.9" align="center" cellpadding="2" cellspacing="1" bgcolor="#FFFFFF">
    
    <tr align="center" valign="middle" bgcolor="#3399CC">
     <td height="30" colspan="4" bgcolor="#FFFFFF">个人简历</td>
    </tr>
    
    <tr height="30">
     <td>用户名:</td>
     <td colspan="3"><input type="text" mane="username" size="25" maxlength="20" placeholder="请输入昵称/姓名"        / required="required" autofocus></td>
     </tr>
     
     <tr height="30">
      <td>邮箱:</td>
      <td colspan="3"><input type="text" mane="email" size="25" maxlength="20" placeholder="123@163.com"/></td>
     </tr>
     
     <tr height="30">
      <td>手机号:</td>
      <td colspan="3"><input type="text" mane="telephone" size="25" maxlength="20"/></td>
     </tr>
     
     <tr height="30">
      <td>密码:</td>
      <td colspan="3"><input type="password" name="pass" size="25" maxlength="5"/></td>
      </tr>
      
     <tr height="30" bgcolor="#00FF00">
      <td>年龄：</td>
      <td><input type="number" name="sz"></td>
      <td>性别：</td>
      <td><input type="radio" name="sex" value="男"/>男
          <input type="radio" name="sex" value="女"/>女
      </td>   
     </tr>
     
     <tr>
      <td>爱好：</td>
      <td><input type="checkbox" name="bobby" value="听音乐"/> 听音乐 
          <input type="checkbox" name="bobby" value="看电影"/>看电影
	      <input type="checkbox" name="bobby" value="打游戏"/>打游戏
	      <input type="checkbox" name="bobby" value="旅游"/>旅游
	      <input type="checkbox" name="bobby" value="打篮球"/>打篮球
       </td>
      </tr>
      <tr>
       <td>所在城市：</td>
       <td><select>
	        <option>--请选择您所在的城市--</option>
	        <option>上海</option>
		    <option>北京</option>
		    <option>成都</option>
		    <option>洛阳</option>
		    <option>郑州</option>
		    <option>南京</option>
	       </select>
        </td>
       </tr>
       
       <tr>
        <td>喜欢的颜色：</td>
        <td><input type="color" name="ys"></td>
       </tr>
       
       <tr>
        <td>工作经历：</td>
        <td><textarea name="sign" cols="30" rows="10"></textarea></td>
       </tr>
       
       <tr>
        <td>选择上传的文件:</td>
        <td><input type="file" name="filename"/></td>
       </tr>  
      
       <tr>
        <td>网址:</td>
        <td><input type="url" name="dz"></td>
       </tr>
       
       <tr>
        <td>日期:</td>
        <td><input type="date" name="rq"></td>
       </tr>
       
       <tr>
        <td>时间:</td>
        <td><input type="time" name="sj"></td>
       </tr>
       
       <tr>
        <td>周:</td>
        <td><input type="week" name="z"></td>
       </tr>
       
       <tr>
        <td>搜索:</td>
        <td><input type="search" name="ss"></td>
       </tr>
       
       <tr>
        <td>亮度:</td>
        <td><input type="range" name="hk"></td>
       </tr>
       
       <tr>
        <td><input type="submit" value="提交"/></td>
        <td><input type="reset" value="重置"/></td>
        <td><input type="button" value="点赞" onclick="javascript:window.alert('您已点赞！谢谢浏览此网页，欢迎下次再来(-_-)嘻嘻...')"/></td>
        <td><input type="button" value="关闭" onclick="javascript:window.close()"/></td>
       </tr>
       
       
      </table>


<!--
 网址:<input type="url" name="dz"><br/>
 日期:<input type="date" name="rq"><br/>
 月份:<input type="month" name="yf"><br/>
 时间:<input type="time" name="sj"><br/>
 周:<input type="week" name="z"><br/>
 搜索:<input type="search" name="ss"><br/>
 颜色:<input type="color" name="ys"><br/>
 亮度:<input type="range" name="hk"><br/>
 个数:<input type="number" name="sz"><br/>
 <input type="hidden" name="id"/>只给程序看<br/>
 

	<input type="submit" value="提交"/>
    <input type="reset" value="重置"/>
    <input type="button" value="点赞" onclick="javascript:window.alert('您已点赞！谢谢浏览此网页，欢迎下次再来(-_-)嘻嘻...')"/>
    <input type="button" value="关闭" onclick="javascript:window.close()"/><br/>

-->




  <div align="center">
    <video controls>
     <source src="资源/视频.mkv">
     <source src="资源/视频.mp4">
     <source src="资源/视频.webm">
    </video>
     <audio src="资源/音乐/丫头.mp3" controls></audio>
 </div>
</body>
</html>
