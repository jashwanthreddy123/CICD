FROM nginx:latest

# Remove default nginx page
RUN rm -rf /usr/share/nginx/html/*

# Copy frontend files
COPY . /usr/share/nginx/html/

EXPOSE 5000

CMD ["nginx", "-g", "daemon off;"]
