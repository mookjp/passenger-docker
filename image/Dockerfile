FROM phusion/baseimage:0.9.16
MAINTAINER Phusion <info@phusion.nl>

# Use Ruby 2.1
ENV ruby21=1

ENV HOME /root
ADD . /pd_build
RUN /pd_build/install.sh
CMD ["/sbin/my_init"]
EXPOSE 80 443
