FROM ubuntu:trusty-20190425
RUN apt-get update && apt-get install -y python3-pip && pip3 install requests --upgrade
COPY knsync.py run.sh /
RUN ["chmod", "+x", "/run.sh"]
ENTRYPOINT ["/run.sh"]