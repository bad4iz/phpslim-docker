
сборка `sudo docker build -t slim-docker:1 .`

запуск `sudo docker run --rm -v $(pwd):/var/www/html/ -v /var/www/html/vendor -p 80:80 slim-docker:1`
