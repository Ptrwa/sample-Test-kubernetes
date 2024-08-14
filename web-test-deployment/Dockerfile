# Gunakan base image httpd (Apache HTTP Server)
FROM httpd:latest

# Salin file HTML ke dalam direktori /usr/local/apache2/htdocs/
COPY versi1/index.html /usr/local/apache2/htdocs/
# COPY versi2/index.html /usr/local/apache2/htdocs/

# Set port yang digunakan oleh container
EXPOSE 80

# Jalankan Apache HTTP Server
CMD ["httpd-foreground"]
