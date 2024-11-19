FROM nginx 
RUN rm -rf /usr/share/nginx/html/*
COPY code /usr/share/nginx/html
RUN rm -rf /usr/share/nginx/conf.d/default.conf
RUN rm -rf /usr/share/nginx/nginx.conf
COPY nginx.conf /usr/share/nginx/nginx.conf