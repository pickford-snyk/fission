FROM perl:5.43.8-trixie

RUN cpanm -n Twiggy Getopt::Args Dancer2

COPY    server.pl /server.pl
WORKDIR /

EXPOSE 8888
ENTRYPOINT ["/server.pl"]
