# python-web-falcon-api-sqlserver-pop

## Description
Simple web app that serves api
for a falcon project.

Uses sqlalchemy query a table `pop`.

## Tech stack
- python
  - falcon
  - uvicorn
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- mssql

## Docker stack
- python:latest
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
- [Availble at](http://localhost/dogs)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Falcon session setup](https://eshlox.net/2019/05/28/integrate-sqlalchemy-with-falcon-framework-second-version)
