FROM centos:latest
MAINTAINER Nathan Williams <nath.e.will@gmail.com

RUN yum makecache fast
RUN yum -y upgrade
RUN curl -L https://www.opscode.com/chef/install.sh | bash -s -- -P chefdk
RUN rm -rf /tmp/*
RUN yum clean all
