FROM nginx
LABEL name="zhihuan-website"
LABEL version="1.0"
COPY  ./dist/ /usr/share/nginx/html/
COPY ./zhihuan-website.conf /etc/nginx/conf.d/
EXPOSE 80