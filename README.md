# netty-source-with-annotation
在netty源码上添加中文注释

本项目基于netty 4.1.50.Final版本

- 使用IDEA打开你的maven工程（工程依赖了netty）
```
<dependency>
  <groupId>io.netty</groupId>
  <artifactId>netty-all</artifactId>
  <version>4.1.50.Final</version>
</dependency>
```
- maven插件下载source和documentation
- File-Project Structure-Libraries中，找到io.netty:netty-all:4.1.50.Final,将Source替换文本项目下载的zip包解压的文件夹
- 打开netty源码时，即可看到本项目添加的中文注释
- 可以在源码中添加自己的注释，注意，不要改变原有代码的行号
