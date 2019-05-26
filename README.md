# 整合IDEA+Maven+SSM框架的高并发的商品秒杀项目

![Mac OS X 10.12.4](https://img.shields.io/badge/Mac%20OS%20X-10.12.4-lightgrey.svg) 
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-2017.2.6-red.svg) 
![Maven](https://img.shields.io/badge/Maven-4.0-ff69b4.svg) 
![SSM](https://img.shields.io/badge/SSM-framework-brightgreen.svg) 
![build](https://img.shields.io/badge/build-passing-brightgreen.svg) 
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/nnngu/nguSeckill/blob/master/LICENSE) 

## 快速部署

1、clone项目到本地

2、数据库脚本放在Seckill项目的sql目录下，在MySQL中执行数据库脚本

3、数据库配置在Seckill项目的src/main/resources目录下的jdbc.properties文件中

4、在IntelliJ IDEA中运行Seckill项目

5、运行成功，enjoy it！

注意事项; 使用eclipse 运行可能会出现各种问题,最好使用idea
          本项目使用mysql版本是8.0.11,如果你是以前的版本,需要修改maven的数据库连接包版本和jdbc.properties中的 jdbc.driver和jdbc.url

