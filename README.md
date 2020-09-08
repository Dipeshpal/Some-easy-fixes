# Some easy fixes-

1. No module pip
	 `easy_install pip`
2. Colab Keep Connection alive-
	```
	function ClickConnect(){  
	console.log("Working");  
	document.querySelector("colab-toolbar-button#connect").click()  
	}  
	setInterval(ClickConnect,60000)
	```
