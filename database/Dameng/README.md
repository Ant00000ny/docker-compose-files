dameng docker 使用文档：https://eco.dameng.com/document/dm/zh-cn/start/dm-install-docker.html

1. 下载 docker image
2. 将 image 重新 tag（替换 `xxx`）：
    ```shell
    docker tag dm8:xxx local:dm8
    ```
3. 启动 docker compose
    ```shell
    docker compose up -d
    ```

Java DM 驱动文件：https://eco.dameng.com/download/ 页面底部

JDBC 驱动使用指南：https://eco.dameng.com/document/dm/zh-cn/app-dev/java-jdbc

默认凭据：SYSDBA / SYSDBA001
