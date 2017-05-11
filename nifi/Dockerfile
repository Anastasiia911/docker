FROM anastasiia911/debian-jdk-8:latest
RUN apk add --no-cache wget && \
    cd /home && \
	wget "http://mirrors.m247.ro/apache/nifi/1.1.2/nifi-1.1.2-bin.tar.gz" && tar -xzf nifi-1.1.2-bin.tar.gz -C /home/ && \
    rm /home/nifi-1.1.2-bin.tar.gz && \	
	apk del wget
EXPOSE 8080
CMD ["/bin/sh"]