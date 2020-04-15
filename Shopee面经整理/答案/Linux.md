1. Linux上怎么查看某端口被什么进程占用

   - ```shell
     lsof -i:端口号
     ```

   - ls open files

   - ```shell
     netstat -tunpl | grep 端口号
     ```

2. 如何修改文件的权限

3. 