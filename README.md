# Docker_Info
Docker desktop 下載
https://docs.docker.com/desktop/install/windows-install/


# GrayLog 安裝指令
docker run --name graylog -d -p 9000:9000 -p 12201:12201/udp -p 1514:1514 graylog/graylog:5.1


# docker 指令參數說明
-name : docker Container 名稱
-p : 本機對應Docker Container的Port Mapping EX : 本機Port:ContainerPort
-e : 設定環境參數(注意如果設定了環境變數，修改元件的Config檔案可能不起作用)
