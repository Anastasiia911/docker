FROM anastasiia911/debian-jdk-8:latest

RUN mkdir /home/nifi && \
    cd /home/nifi && \
	wget "http://mirrors.m247.ro/apache/nifi/1.1.2/nifi-1.1.2-bin.tar.gz" && \
        tar -xzf nifi-1.1.2-bin.tar.gz && \
    rm nifi-1.1.2-bin.tar.gz 	
	
EXPOSE 8080
CMD ["/bin/sh"]