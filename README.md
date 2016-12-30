### 核心特性
* 按照界面步骤轻松生成代码，省去XML繁琐的学习与配置过程
* 保存数据库连接与Generator配置，每次代码生成轻松搞定
* 内置常用插件，比如offset
* 可选的去除掉对版本管理不友好的注释，这样新增或删除字段重新生成的文件比较过来清楚
* 目前已经支持Mysql、Oracle与PostgreSQL，如果有对其它数据库有需求的请提Issue我会跟进。

### 要求
本工具由于使用了Java 8的众多特性，所以要求 JRE或者JDK 8.0以上版本，对于JDK版本还没有升级的童鞋表示歉意。

### 自助构建
    git clone https://github.com/astarring/mybatis-generator-gui
    cd mybatis-generator-gui
    mvn jfx:jar
### 启动本软件
* 方法一: 下载的zip包

解压zip包，如果安装好了JRE或者JDK 8，直接cd至软件目录运行

    java -jar mybatis-generator-gui.jar

* 方法二: 自助构建

    cd target/jfx/app/
    java -jar mybatis-generator-gui.jar

* 方法三: IDE中运行

Eclipse or IntelliJ IDEA中启动, 找到MainUI类并运行就可以了
