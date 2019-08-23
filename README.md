中文说明
========

## 简介:
	本着让python脚本在命令行下输出更有色彩,但是同时python的第三方库中没有有特别好的工具库来实现彩色输出,所以我打算写一第三方库弥补这方面的空白.
## 依赖模块:  
   ctype  
## 安装使用:

	1) git clone git@github.com:spacesec/printc.git.
	2) 将克隆下来的printc文件夹放在..\..\Python3\Lib\site-packages中.//也就是python3安装目录下的\Lib\site-packages
	3) 在您的Python程序头中 "import printc.printc as printc".
	4)如果您想输出一个红色的"中国",您既可以使用printc.printf("中国","red")您也可以使用printc.printRed("中国").
	5)您可以根据printc.的提示来选择您想选择的颜色.
	
## 联系我:

	如果您遇到什么安装或者使用问题,您可以给我发邮件咨询,我的邮箱如下
	邮箱:cyber-security@qq.com

	
English Introduction
========

## About:

	I want to make the outputs of python script to be more colorful on CMD ,but unfortunately i can't find such third-party module.So i decided to write a third-party module to fix up the gap.

## Requirements:
	ctype

## Install&Usage:
	
	1) git clone git@github.com:spacesec/printc.git.
	2) Put the module named "printc" into "..\..\Python3\Lib\site-packages".
	   //"Lib\site-packages" is inside of Python3 directory
	3) At the beginning of your Python script "import printc.printc as printc".
	4) For example:if you want to get a red color "Hello World".You can not only use printc.printf("Hello World","red") but also can use printc.printRed("Hello World").
	5)You can choose your favourite color according to the hints of "printc."
	
## Contact Me:

	You can contact me to consult it if you meet any problems of Install&Usage
	Email:cyber-security@qq.com