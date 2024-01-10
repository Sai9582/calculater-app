FROM ubuntu
USER root
RUN apt update -y \
    && apt install nodejs -y \
    && apt install npm -y
COPY . .
RUN chmod -R 777 calculater
ENTRYPOINT ["npm", "run", "start"]
