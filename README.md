<!DOCTYPE HTML>
<<!DOCTYPE html>
<html>
<head>
		<meta http-equiv="Content-Type" content="text/html;charset=utf-8">
	<title>食物欣赏</title>
</head>
<body>
<h1>食物欣赏</h1>
<h2>食物种类</h2>
<ul>
	<li><a href="#"title="水果">水果</a></li>
	<li><a href="#"title="蔬菜">蔬菜</a></li>
	<li><a href="#"title="肉类">肉类</a></li>
</ul>
<p>回想从前在台湾念书的日子，其中最可怕的景象之一就是路过学校饭堂厨房，看见几个厨师浑身是汗在炒菜，他们用双手挥动一根泥铲在硕大的铁锅里翻来翻去，然后拿起一个纸盒，倒下整整半盒的粉末。那些粉末自然就是味精。<br/>
台湾人酷爱味精，夜市街头的小吃摊上几乎没一样东西是不用味精的（除了<a href="http://www.imooc.com" title="查看">刨冰</a>）。有一种说法，解释这是因为台湾菜或福建菜的特点，它们的味道太“寡”，不用味精就根本吃不出味道。
</p>
<img src="http://img.mukewang.com/52da54ed0001ecfa04120172.jpg"title="随便加的图">
<ul>
	<li>葡萄</li>
	<li>哈密瓜</li>
	<li>苹果</li>
</ul>
<img src="http://img.mukewang.com/52da54ed0001ecfa04120172.jpg"title="随便加的图"><br/>
<img src="http://img.mukewang.com/52da54ed0001ecfa04120172.jpg"title="随便加的图"><br/>
<img src="http://img.mukewang.com/52da54ed0001ecfa04120172.jpg"title="随便加的图"><br/>
<img src="http://img.mukewang.com/52da54ed0001ecfa04120172.jpg"title="随便加的图">
<ol>
	<li>葡萄</li>
	<li>苹果</li>
	<li>哈密瓜</li>
</ol>
<style type="text/css">table tr td,th{border: 1px solid #000;}</style>
<table>
<caption>水果表</caption>
	<tr>
		<th>品名</th>
		<th>数量</th>
		<th>单价</th>
	</tr>
	<tr>
		<th>苹果</th>
		<th>20</th>
		<th>5</th>
	</tr>
	<tr>
		<th>葡萄</th>
		<th>20</th>
		<th>5</th>
	</tr>
	<tr>
		<th>哈密瓜</th>
		<th>20</th>
		<th>8</th>
	</tr>
</table>
<form>
	姓名：
	<input type="text" name="myName">
	<br/>
	密码：
	<input type="password" name="pass">
</form>
<form>
	<label>性别：</label>
	<label>男</label>
	<input type="radio" value="1" name="gender-man">
	<label>女</label>
	<input type="radio" value="2" name="gender-woman">
</form>
<form action="save.<?php  ?>" method="post">
	<label>城市：</label>
	<select>
		<option value="北京">北京</option>
		<option value="上海">上海</option>
		<option value="南京">南京</option>
	</select>
</form>
<form>
	<input type="checkbox" name="checkbox1" value="跑步">跑步
	<input type="checkbox" name="checkbox2" value="旅游">旅游
	<input type="checkbox" name="checkbox3" value="游泳">游泳
</form>
<form method="post" action="save.<?php  ?>">
	<label>联系我们</label>
	<textarea cols="30" rows="10">在这里输入内容...</textarea>
	<input type="submit" value="提交" name="submitBtn">	
</form>

</body>
</html>
