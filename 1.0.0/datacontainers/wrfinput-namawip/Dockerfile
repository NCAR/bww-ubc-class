FROM centos:latest
MAINTAINER John Exby <exby@ucar.edu>
#
ENV WRF_VERSION 3.7.1
RUN mkdir /wrfinput
#
RUN curl -SL https://www.rap.ucar.edu/staff/exby/nam_awip32_16120400.tar.gz | tar -xzC /wrfinput
#
VOLUME /wrfinput
CMD ["true"]
