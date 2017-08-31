# ajax
对ajax的深入了解
+ ajax
全名:Asynchronous JavaScript and XML（异步的 JavaScript 和 XML）。
是一种与数据库交换数据的方法，不在重新刷新页面。
AJAX不是一种新的编程语言，而是一种用于创建更好更快以及交互性更强的Web应用程序的技术。
+ 步骤
``` 
var xml = new XMLHttpRequest(); //创建ajax对象
xml.open("method","url","isAsync");
xml.onload =function(){
};
xml.send();
if(method是get){
  url？id=1&name=2
}else{
  xml.send("id=1,name=2");
}
```
