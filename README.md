
Eclipse使用maven说明




一、配置

1、	下载maven
先到官网下载最新版本:https://maven.apache.org/download.cgi


2、	解压到任意目录
我将其解压到了usr/local目录下
 

3、	配置环境变量
打开一个终端输入 vi ~/.bash_profile，加入环境变量,加入如下代码，完成后输入  source ~/.bash_profile  使命令立即生效
export MAVEN_HOME=${PATH}:/usr/local/apache-maven-3.3.9
export PATH=$PATH:$MAVEN_HOME/bin


 

重新打开一个终端输入：mvn -v，查看是否配置成功
 
4、	在eclipse中配置maven
点击Eclipse->Preferences->Maven->Installations->add选择第二步存放maven的位置
 
二、创建项目

1、开启eclipse，右键new——》other，如下图找到maven project
 
2、选择maven project，显示创建maven项目的窗口
 
4、输入maven项目的基本信息，如下图所示：
 5、最后的结果

 
二、使用

请下载项目 查看源码
