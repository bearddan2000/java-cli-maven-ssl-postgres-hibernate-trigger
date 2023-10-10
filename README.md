# java-cli-maven-ssl-postgres-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

Uses self-sign ssl.

## Tech stack
- java
- maven
  - hibernate
  - hql
  - log4j
  - postgres driver

## Docker stack
- alpine:edge
- maven:3-openjdk-17
- postgres:alpine

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
