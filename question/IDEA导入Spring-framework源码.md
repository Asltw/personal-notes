> 导入源码到IDEA之前需要先预编译

如果是linux或macos系统，则执行以下命令
```sh
# 需进入到Spring源码目录
./gradlew cleaIdea :spring-oxm:compileTestJava
```
如果是windows系统，则执行以下命令
```sh
gradlew.bat cleanIdea :spring-oxm:compileTestJava
```

注意：`必须要预编译，不然随便checkout一个分支出来的话，会发现很多类找不到`
  
