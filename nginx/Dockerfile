FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

# Запуск nginx
CMD ["nginx", "-g", "daemon off;"]
