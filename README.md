# java-cli-buildr-hibernate-db2-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- buildr
  - hibernate
  - hql
  - envers
  - log4j
  - db2 driver

## Docker stack
- vanto/apache-buildr:latest-jruby-jdk8
- ibmcom/db2

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
