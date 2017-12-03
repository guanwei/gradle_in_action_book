Gradle构建脚本默认的名字是`build.gradle`。

通过`-q`告诉Gradle只输出该task相关的信息。
```
$ gradle -q helloWorld
Hello World!
```

名字为doLast的action是task执行的最后一个action，使用左移符号<<来简单地代表doLast。

dependsOn是task的一个方法。

列出项目中的所有可用的task
```
$ gradle -q tasks
```

获取task更多信息
```
$ gradle -q tasks --all
```