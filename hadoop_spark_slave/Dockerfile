FROM prass016/hadoop_spark_base:latest
MAINTAINER SrinivasaPrasadA

USER root

ADD start_up.sh /etc/start_up.sh
RUN chown root:root /etc/start_up.sh && \
    chmod 700 /etc/start_up.sh

CMD ["/etc/start_up.sh", "-d"]
