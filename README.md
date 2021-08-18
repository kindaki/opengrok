关于如何安装配置opengrok
1.安装tomcat9
  sudo apt-get install tomcat9
2.执行脚本
  java -jar ./lib/opengrok.jar -P -S -v -s ./src -d ./data -I *.java -I *.c -I *.h -I *.cpp -W ./configuration.xml
3.cp
  cp ./lib/source.war /var/lib/tomcat9/webapps/
