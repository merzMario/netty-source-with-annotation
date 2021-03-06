# netty-source-with-annotation
在netty源码上添加中文注释

1.使用IDEA创建或导入工程后，添加netty-all依赖
<dependency>
  <groupId>io.netty</groupId>
  <artifactId>netty-all</artifactId>
  <version>4.1.50.Final</version>
</dependency>

2.maven插件下载source和documentation
3.File-Project Structure-Libraries中，找到io.netty:netty-all:4.1.50.Final,将Source替换文本项目下载的zip包解压的文件夹
4.打开netty源码时，即可看到本项目添加的中文注释
5.可以在源码中添加自己的注释，注意，不要改变原有代码的行号
