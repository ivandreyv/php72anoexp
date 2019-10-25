# php72anoep
Based on php:7.2-apache (https://github.com/docker-library/php/tree/master/7.2/buster/apache)
But for azure web app deploy here was deleted EXPOSE value.
So to run docker it need to do:

docker run -p $EXT_PORT:$INT_PORT -e port$INT_PORT ivandreyv/php72anoexp:$tag 

