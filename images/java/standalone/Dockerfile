FROM debian:11

RUN apt update
RUN apt install -y wget maven
RUN wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie" https://download.oracle.com/java/17/latest/jdk-17_linux-x64_bin.tar.gz
RUN cd /usr/lib/jvm && tar -xvzf /jdk-17_linux-x64_bin.tar.gz
ENV JAVA_HOME="/usr/lib/jvm/jdk-17"
ENV PATH="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games"