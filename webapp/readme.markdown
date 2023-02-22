# mysql 配置

1. 在 **./mysql/conf** 目录下 新建  **custom.conf** 并写入内容

   > [mysqld]
   > skip-name-resolve

   ```shell
   cd ./mysql/conf && echo -e "[mysqld]\nskip-name-resolve" > custom.conf
   ```

   