FROM debian:bookworm-slim

RUN apt-get update
RUN apt-get install -y rtl-433
#RUN apt-get install -y rtl-sdr
#RUN apt-get install -y locales
RUN rm -rf /var/lib/apt/lists/* 
#RUN localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
#ENV LANG en_US.utf8

#RUN apt install --no-cache -y --no-install-recommends nginx
