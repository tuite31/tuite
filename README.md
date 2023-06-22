# tuite
on (press) {

getURL("xxx.com","_blank");

}

<body oncontextmenu="return false" ondragstart="return false" onselectstart ="return false" 

onselect="document.selection.empty()" oncopy="document.selection.empty()" 

onbeforecopy="return

false"onmouseup="document.selection.empty()"> 

<body oncontextmenu="window.event.returnValue=false" 

onkeypress="window.event.returnValue=false" 

onkeydown="window.event.returnValue=false" 

onkeyup="window.event.returnValue=false" 

ondragstart="window.event.returnValue=false" 

onselectstart="event.returnValue=false"> 

</body>
<Script Language="JavaScript"> 

　　 image = new Array(4); //定义image为图片数量的数组 

　　 image [0] = 'tu0.gif' //背景图象的路径 

　　 image [1] = 'tu1.gif' 

　　 image [2] = 'tu2.gif' 

　　 image [3] = 'tu3.gif' 

　　 image [4] = 'tu4.gif' 

　　 number = Math.floor(Math.random() * image.length); 

　　 document.write("<BODY BACKGROUND="+image[number]+">"); 

</Script> 

