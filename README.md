Dockerfile for pgbouncer
===

docker image for pgbouncer based off of stackbrew/ubuntu:12.04

To build this image:

docker build -t isensible/pgbouncer .

To run: 

docker run -i -t -d -p 6432:6432 --link POSTGRES_NAME:pg isensible/pgbouncer


