FROM ubuntu:16.04
RUN apt-get update && apt-get install -y bc git
RUN git clone https://github.com/sweettooth90/bc-plus.git
RUN chmod a+x /bc-plus/plus.sh
ENTRYPOINT ["/bc-plus/plus.sh"]
