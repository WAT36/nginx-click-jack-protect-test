FROM nginx:latest

COPY ./default.conf /etc/nginx/conf.d/default.conf
RUN nginx -t
RUN service nginx restart