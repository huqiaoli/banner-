js ��ȡԪ����������li�����ַ���
// var content=document.getElementById("box");
// var items=content.getElementsByTagName("ul");
// var lis=items[0].getElementsByTagName("li");//��ȡbox�µ�һ��ul��li����
// console.log(lis)

��
// var content=document.getElementById("box");
// var items=box.childNodes.item(0);
// var lis=item.children;

window.onload=function(){
  var div=document.getElementById("star");   
  var objul=div.getElementsByTagName("ul")[0];//getElementsByTagName("ul")[0]��õ�һ��ulԪ��
  var lis=objul.getElementsByTagName("li")
}
window.onload=function(){
  var div=document.getElementById("star");   
  var objul=div.getElementsByTagName("ul");//getElementsByTagName("ul")���һ��ulԪ�ؼ���
  var lis=objul[0].getElementsByTagName("li")//getElementsByTagName�����Elements�и�s����ζ�Ż�ȡ���Ƕ��Ԫ�أ������õ���ularr[0]����ʹֻ��һ����Ҳ�������鷽ʽ��ʾ��;
}
getElementsByTagName �����������һ����������Ķ��󣬷����������������±�������
��0������ȡ���һ���ע����elements �Ǹ�S ˵���Ǹ�������ģ���Ҳ����ѭ���������ʶ����Ա��
var subMenu = li.getElementsByTagName("ul");//ul �ļ���
for(var i=0;i<subMenu.length;i++){
alert(subMenu[i].id)//������ʼ����е�Ԫ��