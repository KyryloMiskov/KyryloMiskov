FROM centos
RUN yum -y install nc
COPY . .
RUN chmod 755 websrb.sh
CMD "./websrb.sh"
EXPOSE 8080/tcp
