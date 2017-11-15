# centos7-java8
Docker image containing installation of Oracle JDK 1.8 on CentOS 7

## Usage

In order to run it, issue the following command

    $ docker container run -it --rm bloque/centos7-java8 bash

Inside the container's shell one can verify the installation of java as shown below 

```sh
$ java -version
java version "1.8.0_151"
Java(TM) SE Runtime Environment (build 1.8.0_151-b12)
Java HotSpot(TM) 64-Bit Server VM (build 25.151-b12, mixed mode)
$ echo $JAVA_HOME
/usr/java/jdk1.8.0_151/jre
```
