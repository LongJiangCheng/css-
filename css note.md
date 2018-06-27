为元素命名：在分配Id和Class名时，要尽量保持名字与表现方式无关
伪元素【::first-line,::first-letter,::before,::after】:在HTML中并不存在，它们只是另一个元素的部分内容
伪类[:first-child,:link,:hover and so on]:则应用于一组HTML元素。
/**
* link是未访问，未指向的外观
* visited 访问过的外观
* focus 获得焦点时的外观,一般通过tab键来激活。
* hover 鼠标放在链接上面时的外观
* active 鼠标点下未散开时的外观
* 建议使用以上顺序
a:link{
	color:red;
}
a:visited{
	color:orange;

}
a:focus{
	color:purple;
}
a:hover{
	color:green;
}
a:active{
	color:blue;
}
**/
注：也可以对其它类型的元素使用：active和:hover伪类。
