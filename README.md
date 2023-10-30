# groovy-cli-bazel-dolt-simple

## Description
A groovy bazel build, that connects to dolt database.

## Tech stack
- groovy
- bazel
  - 6.8.2

## Docker stack
- dolthub/dolt-sql-serverdb:latest
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
