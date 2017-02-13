js 获取元素下面所有li的两种方法
// var content=document.getElementById("box");
// var items=content.getElementsByTagName("ul");
// var lis=items[0].getElementsByTagName("li");//获取box下第一个ul里li集合
// console.log(lis)

或
// var content=document.getElementById("box");
// var items=box.childNodes.item(0);
// var lis=item.children;

window.onload=function(){
  var div=document.getElementById("star");   
  var objul=div.getElementsByTagName("ul")[0];//getElementsByTagName("ul")[0]获得第一个ul元素
  var lis=objul.getElementsByTagName("li")
}
window.onload=function(){
  var div=document.getElementById("star");   
  var objul=div.getElementsByTagName("ul");//getElementsByTagName("ul")获得一个ul元素集合
  var lis=objul[0].getElementsByTagName("li")//getElementsByTagName里面的Elements有个s，意味着获取的是多个元素，所以用的是ularr[0]（即使只有一个，也得用数组方式表示）;
}
getElementsByTagName 这个方法返回一个类似数组的对象，访问数组对象可以用下标来访问
【0】就是取其第一项，（注意是elements 那个S 说明是个数组类的），也可以循环遍历访问对象成员。
var subMenu = li.getElementsByTagName("ul");//ul 的集合
for(var i=0;i<subMenu.length;i++){
alert(subMenu[i].id)//这里访问集合中的元素


[九种原生js动画效果](http://www.jb51.net/article/74686.htm) 
