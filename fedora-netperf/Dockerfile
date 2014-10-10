FROM fedora
MAINTAINER Mrunal Patel <mrunalp@gmail.com>

RUN yum install -y gcc make
RUN curl -O ftp://ftp.netperf.org/netperf/netperf-2.6.0.tar.gz
RUN tar xvzf netperf-2.6.0.tar.gz
RUN cd netperf-2.6.0 && ./configure && make && make install

CMD ["/bin/bash"]

