FROM vdonkor/jenkins-agent

MAINTAINER vincent donkor

USER root
#Install setup tool for ansible
RUN yum install -y python-setuptools \
  && yum clean all

# Install ansible
RUN easy_install pip && pip install ansible

