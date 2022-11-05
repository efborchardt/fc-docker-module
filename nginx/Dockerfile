FROM nginx:latest

COPY HTML /usr/share/nginx/html

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx" "-g" "daemon off;"]