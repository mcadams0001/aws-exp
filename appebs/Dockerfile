FROM httpd:latest
ENV LICENSE=12345678
ENV LOCATION=US
WORKDIR /usr/local/apache2/htdocs
RUN echo "<html><body>License: ${LICENSE}<br/>Location:${LOCATION}</body></html>" > info.html
EXPOSE 80