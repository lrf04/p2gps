FROM mongo:3.4

MAINTAINER luis.ruiz2@alu.uclm.es

COPY drop/* /usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]