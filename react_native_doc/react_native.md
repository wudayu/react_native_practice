## React Native分享 

####一.基本概念
1. React Native是使用React来进行开发的前端框架。可以用来开发基于iOS，Android等移动平台的App应用。
2. React Native基于Virtual DOM。不同于传统的H5开发模式，React Native通过VDOM封装了不同平台（iOS或Android）上的原生控件，同时通过VDOM向开发者暴露了相同的使用方式的UI控件。这一点大大提高了程序的运行效率。  
![](./structure.png =350x)
3. React Native的思想是**“Learn once, write anywhere”**，而不是类似于Java的**“Write once, run anywhere”**。
4. 就目前而言，React Native还处于刚起步阶段，Android平台的支持也刚刚发布。各方面问题也相对较多。但随着Facebook的推广，其零散的问题也会逐渐被解决。毕竟其实现方式是比现在比较流行的H5App开发方式（如：Ionic+Cordova+AngularJs），更为新颖与振奋人心的。其发展前景值得期待。

####二.开发工具与安装
#####1.开发工具
* IDE：Intellij IDEA Ultimate / Sublime / 普通记事本。    
* Node.js（4.0以上，包含npm），npm是比较常用的前端包管理命令，包含在Node.js环境中，今后很多工具需要使用npm下载。建议安装最新版Node.js，安装完成后，npm的使用环境也就建好了。此外React Native需要Node-4.0以上版本支持。  
* 终端
* Android环境，安装Android SDK，或者直接安装Android Studio环境（IDE+SDK）。
* iOS环境，安装xcode与最新iOS的SDK。

#####2.安装
请到各个官网查看以上开发工具在不同平台上的安装方式。
####三.基本用法与Demo
请至 <https://github.com/wudayu/react_native_practice>下载查看代码实例。  
安装React Native开发环境：  
![](./install.png =600x "安装React Native")  
阅读代码时，请注意以下几点：    

* 目录的结构。  
* 如何运行各个不同平台。
* 代码的结构。
  
####四.技术对比
		目前比较火的跨平台开发框架是Ionic+Cordova+AngularJs（以下简称ICA），其使用的是App常规的WebView套一个App的壳。而React Native生成的App不是运行在WebView上，是系统原生的UI，React通过jsx生成系统原生的UI，iOS和Android的React UI组件还是比较相似的，大量代码可以复用。
		ICA的开发环境比较简单，Win，Linux，Mac都可以搭建ICA的开发环境。而React Native则只能在Mac上开发。这点比较容易理解：ICA使用的是H5的控件，准确的说他是不具有平台依赖性的。而React Native使用的是各个平台的原生控件，需要相应的环境，而iOS的相关开发必须要在Mac机器上进行，所以React Native只能在Mac机器上进行。
