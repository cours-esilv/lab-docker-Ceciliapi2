FROM nginx:latest
ENV WS_BACK_URL=http://172.17.0.2:5000
COPY . /usr/share/nginx/html
ENTRYPOINT ["nginx", "-g", "daemon off;"]
EXPOSE 80
