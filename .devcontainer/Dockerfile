FROM centos

RUN yum groupinstall -y 'Development Tools' \
    && yum install -y pcre pcre-devel \
    && yum install -y zlib zlib-devel \
    && yum install -y openssl openssl-devel

RUN  mkdir -p /usr/local/nginx/html /usr/local/nginx/logs

EXPOSE 80
