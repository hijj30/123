4 лаб работа

за основу я взял уже готовый html файл с использованием js из интернета


создал dockerfile в корне репозитория и в него прописал следующий код

FROM nginx

COPY js.html /usr/share/nginx/html

COPY style.css /usr/share/nginx/html

COPY script.js /usr/share/nginx/html


после чего я создал docker образ 

docker build -t js

и запустил его

docker run -d -p 80:80 js
