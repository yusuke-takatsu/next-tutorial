FROM node:18.16.0-slim

RUN apt-get update && \
    apt-get install -y git

WORKDIR /app

ENV CHOKIDAR_USEPOLLING=true
ENV LANG=C.UTF-8
ENV TZ=Asia/Tokyo

CMD ["/bin/bash"]