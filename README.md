# 阅读Dubbo的源码
> 快速掌握RPC的方式就是去阅读源码，所以，我决定去阅读这个源码，也就是最新的分支2.5.6这个分支上的源码


## 打包代码
这个是我的打包方式

 ```$xslt
"D:\Program Files\Java\jdk1.8.0_171\bin\java.exe" -Dmaven.multiModuleProjectDirectory=E:\codeworld\readcode\dubbo "-Dmaven.home=D:\Program Files\apache-maven-3.5.0" "-Dclassworlds.conf=D:\Program Files\apache-maven-3.5.0\bin\m2.conf" -javaagent:C:\Users\Administrator\AppData\Local\JetBrains\Toolbox\apps\IDEA-U\ch-0\182.4892.20\lib\idea_rt.jar=53579:C:\Users\Administrator\AppData\Local\JetBrains\Toolbox\apps\IDEA-U\ch-0\182.4892.20\bin -Dfile.encoding=UTF-8 -classpath "D:\Program Files\apache-maven-3.5.0\boot\plexus-classworlds-2.5.2.jar" org.codehaus.classworlds.Launcher -Didea.version=2018.2.5 -s E:\maven\settings.xml install

```
