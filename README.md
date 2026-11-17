Task 1

<img width="1706" height="233" alt="image" src="https://github.com/user-attachments/assets/3e0bb3ad-16a5-4e41-b9e4-5710ce489fca" />

Task 2

<img width="1361" height="768" alt="image" src="https://github.com/user-attachments/assets/a41a4e6c-47f5-4bf4-960f-fbe1eab0e0eb" />

<img width="1711" height="810" alt="image" src="https://github.com/user-attachments/assets/908c4565-1ece-497a-a821-1473b089b6c4" />

К сожалению, скришоты не прикладываются, ошибка something went really wrong and we can't process that file
Поэтому вывод текстом по проверкам ниже:


NAME               IMAGE
web-first-nginx    nginx:1.28.0
web-first-redis    redis:7.4.2
web-second-nginx   nginx:1.28.1
web-second-redis   redis:7.4.2
web-third-nginx   nginx:1.28.1
web-third-redis   redis:7.4.2

curl -I http://10.152.183.44
HTTP/1.1 200 OK
Server: nginx/1.28.0
Date: Tue, 17 Nov 2026 14:00:15 GMT

curl -I http://10.152.183.60
HTTP/1.1 200 OK
Server: nginx/1.28.1
Date: Tue, 17 Nov 2026 14:00:21 GMT

curl -I http://10.152.183.94
HTTP/1.1 200 OK
Server: nginx/1.28.1
Date: Tue, 17 Nov 2026 14:00:26 GMT
