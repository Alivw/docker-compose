# mysql 配置

1. 在 **./mysql/conf** 目录下 新建  **custom.conf** 并写入内容

   > [mysqld]
   > skip-name-resolve

   ```shell
   echo -e "[mysqld]\nskip-name-resolve" > mysql/conf/custom.cnf
   ```


![image-20230303105831436](readme/img/image-20230303105831436.png)