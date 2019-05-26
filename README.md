# 整合IDEA+Maven+SSM框架的高并发的商品秒杀项目


## 快速部署

1、clone项目到本地

2、新建数据库：数据库脚本放在Seckill项目的sql目录下，在MySQL中执行数据库脚本

3、数据库配置：在Seckill项目的src/main/resources目录下的jdbc.properties文件中，修改密码

4、在IntelliJ IDEA 配置tomcat服务器 <br>
   修改项目默认打开路径：run configuration —> url 修改为/  <br>
   修改 默认上下文路径：run configuration --> deployment application context 通过修改为/ <br>

5、运行tomcat 会显示默认主页

注意事项; 使用eclipse 运行可能会出现各种问题,最好使用idea  
         本项目使用mysql版本是8.0.11,如果你是以前的版本,需要修改maven的数据库连接包版本和jdbc.properties中的 jdbc.driver和jdbc.url

