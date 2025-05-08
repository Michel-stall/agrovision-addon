FROM nginx:alpine

# Entferne die Standard-NGINX-Konfiguration (die auf 8123 oder 80 lauscht)
RUN rm /etc/nginx/conf.d/default.conf

# Kopiere deine eigene nginx.conf mit Port 8848
COPY nginx.conf /etc/nginx/nginx.conf
