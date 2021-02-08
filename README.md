docker run --name nginx-proxy -v /home/pierangelo/lavori/glocal/demo_grafici:/var/www/html -d -p 8080:80 nginx


docker run -it --rm -d -p 8080:80 --name web -v /home/pierangelo/lavori/glocal/demo_grafici:/usr/share/nginx/html nginx