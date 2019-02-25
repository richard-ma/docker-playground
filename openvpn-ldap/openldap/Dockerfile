FROM centos/systemd

MAINTAINER "Richard Ma" <richard.ma.19850509@gmail.com>

RUN yum -y install openldap compat-openldap openldap-clients openldap-servers openldap-servers-sql openldap-devel; yum clean all; systemctl enable slapd;

EXPOSE 389 

CMD ["/usr/sbin/init"]
