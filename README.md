# Optimized container for Nginx with very secure SSL and mod security enabled

## What is it

This Dockerfile gives you a ready to use secured production Nginx server, with perfectly configured SSL. You should get a A+ Rating at the Qualys SSL Test.

    docker run -d \
    -p 80:80 -p 443:443 \
    -v $EXT_DIR:/etc/nginx/conf.d/ \
    nginx-mod_security

## Based on

This Dockerfile is based on the Alpine Official Image.
