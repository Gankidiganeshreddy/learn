FROM centos
MAINTAINER ganesh <ganeshreddy.gankidi@gmail.com>
RUN yum install git -y
RUN git clone https://github.com/abhiramIT/html.git /var/www/html
CMD ["httpd","-DFOREGROUND"]
