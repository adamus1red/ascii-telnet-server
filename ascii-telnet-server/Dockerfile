FROM python:3.13.5-alpine
MAINTAINER Rohan Singh "rohan@washington.edu"

ADD ascii-telnet-server.py /root/
ADD sw1.txt /root/

EXPOSE 23

ENTRYPOINT ["python", "/root/ascii-telnet-server.py"]
CMD ["-f", "/root/sw1.txt"]
