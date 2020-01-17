FROM ubuntu:14.04
RUN touch /bin/irpf-2018
RUN echo "#!/usr/bin/env bash" > /bin/irpf-2018; \
    echo "[ ! -d /usr/local/IRPF2018/ ] && ./IRPF2018Linux-x86_64v1.4.bin" >> /bin/irpf-2018; \
    echo "/usr/bin/java -Xms128M -Xmx512M -jar /usr/local/IRPF2018/irpf.jar" >> /bin/irpf-2018; \
    chmod u+x /bin/irpf-2018; \
    apt-get update; \
    apt-get install -y openjdk-7-jdk; \
    apt-get install -y wget
RUN wget http://downloadirpf.receita.fazenda.gov.br/irpf/2018/irpf/arquivos/IRPF2018Linux-x86_64v1.4.bin; \
    chmod u+x IRPF2018Linux-x86_64v1.4.bin; \    
    mkdir /root/shared
