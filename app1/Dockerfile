FROM nginx:latest
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "<h1>Am from app1</h1>" >/usr/share/nginx/html/index.html
CMD ["sleep","300s"]