# -
期中
<input>可輸入 <type>型態
<tr>、</tr>、(tr)列
<td></td>、(td)欄
<br> 換行
Rowspan列擴展
Heaf屬性
Value值
Body主體
Title標題
Font-size字的大小
Caption表格的標題
Login.php會得到密碼，所以不安全
預設值，可輸入可不用
1、	網頁設計 
01<!DOCTYPE html>
02<html>
03  <head>
04    <meta charset="utf-8">
05    <title>我的網頁</title> title網頁名稱
06    <style type="text/css">
07      h1 {font-size:30px; color:blue} 標題1 文字大小及顏色
08    </style>
09  </head>
10  <body> 網頁主體
11    <h1>你被騙了!</h1> 標題1
12  </body>
13</html>
2、	網頁視窗
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>我的網頁</title>
<script>alert("WELLCOME");</script>堪入程式
</head>
<body>
</body>
</html>
3、	圖片插入
<img src="月月.jpg" width="100%"> 圖片一定要打全名!否則找不到照片
<figcaption>月月的故事 </figcaption>圖片標題

4、	表格
<caption>座位表</caption> 標題
<tr><th>編號</th><th>姓名</th></tr><tr><td>1</td><td>2</td></tr><tr><td>3</td><td>4</td></tr><tr><td>5</td><td>6</td></tr></table>
座位表
1	4
2	5
3	6

5、	表單
<form>
姓名：<input type="text" name="userName" size="20"></p>03 不可忘記
密碼：<input type="password" name="userPWD" size="20"></p>
只要提到PWD前面就是存入數值
<input type="submit" value="提交">
<input type="reset" value="重新輸入">
</form>
 
 
6、舉例           
 <form method="get" action="registration.php">由後方哪個程式處理
 姓名:<input type="text" name="name"><br>文字                      
 性別: <input type="radio" name="gender" value="M">男
      <input type="radio" name="gender" value="F">女   表單選項按鈕
       <input type="radio" name="gender" value="N">無法透漏<br> 
興趣:<input type="checkbox" name="interest" value="tv" checked>看電視  
<input type="checkbox" name="interest" value="fish">釣魚
<input type="checkbox" name="interest" value="movie" >看電影<br>                                         表單選取式       預設值可用可不用
 居住地: <select name="county">
         <option value="hsinchu">新竹</option>
         <option value="taoyuan">桃園</option>    表單下拉式 選單
        <option value="miaoli"selected>苗栗</option> 預設值可用可不用
自傳:<br>
<textarea name="autobiography" rows="5" cols="40"></textarea><br> 文字欄位
<input type="submit" value="註冊">       5行 40個字
<input type="reset" value="清除">
♢input只要打一個就好，不需雙雙成對

7、超連結
<a href="https://www.must.edu.tw/ ">歡迎來到明新科大</a>
