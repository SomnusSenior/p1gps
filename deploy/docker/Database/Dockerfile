FROM mongo:3.4

MAINTAINER leonardo.cardozo@alu.uclm.es

COPY drop/* usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]