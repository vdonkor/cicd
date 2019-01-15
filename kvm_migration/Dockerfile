#
# tool for kvm migrations service
#
FROM vdonkor/jenkins-agent
MAINTAINER vdonkor

USER root
RUN yum -y update \
 && yum -y install qemu-utils virsh virt-v2v libguestfs-winsupport
