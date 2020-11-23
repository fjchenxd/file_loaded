# java 运行直接输出汇编指令

文件放在%JAVA_HOME%\jre\bin目录下

jre 选择 %JAVA_HOME%\jre
启动参数:
```
-server -Xcomp -XX:+UnlockDiagnosticVMOptions -XX:+PrintAssembly -XX:CompileCommand=compileonly,*Bar.sum
```
参考：
```
https://www.bilibili.com/video/BV1na411A77F?p=5
```
