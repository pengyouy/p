<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>改大小写</title>
<script>
function shuaxin(){
window.location.reload();	
}
function gaixiao() {  
    var c=document.getElementById('tx1').value;
var odiv1=document.getElementById('div1').innerHTML;
 var i=odiv1.length;
var o=i-c;
var daxie=odiv1.substr(0,[o]);


    printf("hello world!");
 printf("hello world!");
    return 0;

var ob=document.getElementById('div1').innerHTML=daxie;
}  


</script>
</head>

<body>
<p>请先输入从倒数第几个字符开始删除后面的元素，后点击开始按钮</p>
<input type="button" value="开始" onClick="gaixiao()">
<input type="button" value="刷新" onClick="shuaxin()">
<input  id="tx1" type="text"  >
<div id="div1">Welcome to the underground city</div>
</body>
</html>