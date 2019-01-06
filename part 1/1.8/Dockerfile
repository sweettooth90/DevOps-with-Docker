FROM ubuntu:16.04
RUN apt-get update && apt-get install -y bc git
RUN git clone https://github.com/sweettooth90/bash-plus.git
RUN chmod a+x /bash-plus/plus.sh
ENTRYPOINT ["/bash-plus/plus.sh"]
