Tomcat-Research
==================

Tomcat源代码学习研究(包括代码注释、文档、用于代码分析的测试用例)


## 使用的Tomcat版本

保持与官方的[trunk](https://github.com/apache/tomcat)版本同步


## 构建与运行环境

需要JDK7以及[Apache Maven](http://maven.apache.org/)

## 导入IntelliJ IDEA
任何程序都有入口，对于Tomcat来说就是Bootstrap.main()方法，现在就可以来进行运行配置了:
1. 点击Run->Edit Configuration,添加一个新的配置，选择Application
2. MainClass：直接搜索Bootstrap，_VM options:-Dcatalina.home=catalina-home -Dcatalina.base=catalina-home -Djava.endorsed.dirs=catalina-home/endorsed -Djava.io.tmpdir=catalina-home/temp -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager -Djava.util.logging.config.file=catalina-home/conf/logging.properties,
3. Use classpath.....:为Tomcat-Research-Trunk.
4. 运行吧，骚年




<p>最后，打开你的浏览器，输入 http://127.0.0.1:8080/examples/ 看看例子吧。
