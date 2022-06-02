1. 创建 MySQL 数据库 seamall，导入 db_mall_starsea.sql 文件；
2. 修改配置文件（application.properties）中数据库名、用户名、密码；
3. 浏览器上访问 localhost:8080 即可；
4. 前台用户密码自行注册，后台用户名：starsea，密码：111111；
5. 如果需要上传到服务器，则需要按照以下步骤打包：
   1. 点击 idea 右侧边栏的 Maven -> starsea-mall -> Lifecycle -> clean
   2. 点击 idea 右侧边栏的 Maven -> starsea-mall -> Lifecycle -> install
   3. 将项目文件夹下的 target/starsea-mall-0.0.1-SNAPSHOT.jar 上传到服务器
   4. 按照第一、二步，在服务器上配置相同的 MySQL 环境