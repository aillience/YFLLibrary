# YFLLibrary
依赖库添加测试，导入测试弄的项目；<br>
很奇怪一个完整的项目添加依赖失败了？？不知道是肿么回事；<br>
这个貌似成功了。
<br>项目的gradle添加<br>
	allprojects {<br>
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; repositories {<br>
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	...<br>
		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  maven { url 'https://jitpack.io' }<br>
		}<br>
	}<br>
<br>APP的gradle添加<br>
  	dependencies {<br>
	  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;compile 'com.github.aillience:YFLLibrary:v1.0.0'<br>
	}<br>
