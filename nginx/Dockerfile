FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
COPY conf/jenkins.conf /etc/nginx/conf.d/jenkins.conf
COPY conf/nginx.conf /etc/nginx/nginx.conf