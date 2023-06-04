для выполнения лабораторной работы №2 я использовал эти команды:

docker pull nginx

touch kanye.html

apk update && apk add nano

nano kanye.html

docker run -d -p 80:80 nginx

docker cp kanye.html confident\_faraday:/usr/share/nginx/html/kanye.html

docker pull httpd

docker cp /local/path/to/your/kanye.html confident\_faraday:/usr/local/apache2/htdocs/kanye.html



