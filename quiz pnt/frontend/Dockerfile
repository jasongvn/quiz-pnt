# Gunakan base image Nginx
FROM nginx:latest

# Salin file index.html dari direktori build konteks ke dalam container
COPY ./index.html /usr/share/nginx/html/index.html

# Ekspos port 80
EXPOSE 80

# Jalankan Nginx
CMD ["nginx", "-g", "daemon off;"]
