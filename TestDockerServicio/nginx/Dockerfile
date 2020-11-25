FROM nginx:latest
RUN rm /etc/nginx/conf.d/default.conf
RUN mkdir -p /etc/nginx/ssl/aplicacion/
#COPY server.trucupei.com.ve.crt /etc/nginx/ssl/aplicacion/
#COPY key.pem /etc/nginx/ssl/aplicacion/
COPY nginx.conf /etc/nginx/conf.d/default.conf
