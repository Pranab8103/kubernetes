FROM nginx:1.17-alpine 
COPY index.html /usr/share/nginx/html 
COPY nginx.conf /etc/nginx/
EXPOSE 9080
CMD ["nginx", "-g", "daemon off;"]
