# titanic_db_backend
## 路徑:
<img width="782" height="357" alt="image" src="https://github.com/user-attachments/assets/84438300-60ed-4b34-9460-378782641f16" />

## step 1
cd到docker_pymysql_flask
執行

`docker build -t python3_image01 .`

## step 2
回到titanic-share

`cd ../`

確定mysql映像檔版本，我預設是mysql:8.0.44，如果是mysql:8.0，修改docker-compose.yml

`nano docker-compose.yml`

## step 3
執行docker compose up
`docker compose up`

## step 4
在Vscode打開frontend__Open_in_vscode_Edit_your_vm_ip.html
修改fetch內容為你的虛擬機位址

`line 41:  fetch('http://192.168.24.6:5000/titanic', ...`
啟動html後應可預覽結果
