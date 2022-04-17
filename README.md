# docker-compose parallel
Docker multiple Image pull using docker-compose 

# Create a docker-compose.yml file as below.
version: '3.1'
services:
  centos:
    image: centos
  ubuntu:
    image: ubuntu
  php:
    image: php
  node:
    image: node
  tomcat:
    image: tomcat
  python:
    image: python
  apache:
    image: httpd
  nginx:
    image: nginx
  redis:
    image: redis
  mysql:
    image: mysql
  golang:
    image: golang
  mongo:
    image: mongo
  consul:
    image: consul
  elasticsearch:
    image: elasticsearch:8.1.2
  mongo-express:
    image: mongo-express
  jenkins:
    image: jenkins/jenkins:lts-jdk11
  kibana:
    image: kibana:8.1.2
  drupal:
    image: drupal
  rocker.chat:
    image: rocket.chat
  backdrop:
    image: backdrop
  postfixadmin:
    image: postfixadmin

# Then run command as below
docker-compose pull --parallel

