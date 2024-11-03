#latests ---> latest
FROM nginx:latest                                     
COPY nginx.conf /etc/nginx/nginx.conf

# created index.html inside nginx/html
# htmll ---> html 
COPY ./html /usr/share/nginx/html

# "eighty"---> 80
EXPOSE 80

# of ---> off
CMD ["nginx", "-g", "daemon off;"]