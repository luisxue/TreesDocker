FROM centos:7
MAINTAINER AT <luisxuee@gmail.com>

ENV TZ "Asia/Shanghai"


RUN yum -y install epel-release && \
    yum -y update 

RUN    yum install -y gcc automake autoconf libtool make gcc-c++ vixie-cron  wget zlib  file openssl-devel sharutils zip  bash vim cyrus-sasl-devel libmemcached libmemcached-devel libyaml libyaml-devel unzip libvpx-devel openssl-devel ImageMagick-devel  autoconf  tar gcc libxml2-devel gd-devel libmcrypt-devel libmcrypt mcrypt mhash libmcrypt libmcrypt-devel libxml2 libxml2-devel bzip2 bzip2-devel curl curl-devel libjpeg libjpeg-devel libpng libpng-devel freetype-devel bison libtool-ltdl-devel net-tools && \
    yum clean all
    
#Sphinx
RUN cd /tmp && \
  wget 

ADD ..
ADD ..


EXPOSE 9396
#启动Sphinx
ENTRYPOINT []
