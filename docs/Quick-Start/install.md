# Scala 安装



## 确保已安装 Java 环境

```bash
$ java -version
java version "1.8.0_151"
Java(TM) SE Runtime Environment (build 1.8.0_151-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.151-b12, mixed mode)
```



## 安装 Scala

> - https://www.scala-lang.org/download/#download-binaries
> - https://www.scala-lang.org/download/#other-releases

```bash
$ sudo vim /etc/profile
export SCALA_HOME=/Users/kail/Scala/scala-2.12.9/
export PATH="$PATH:$SCALA_HOME/bin"

$ source /etc/profile

$ scala -version
Scala code runner version 2.12.9 -- Copyright 2002-2019, LAMP/EPFL and Lightbend, Inc.
```