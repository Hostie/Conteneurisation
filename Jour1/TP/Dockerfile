ARG VERSION=alpine
FROM nginx:$VERSION
ARG VERSION
RUN apk update && apk upgrade
ENV TIMEZONE Europe/Paris
EXPOSE 80
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
-------  docker run -(d) -p 8000:80 -v pwd/conf:nginxconf -v pwd/html:html       -------------