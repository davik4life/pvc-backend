# pvc-backend
=============

Backend for Find-PVC app for Lagos React group, written in flask/python3

It contains 2 parts:

1. A flask app that serves as an api to query for data returning json

2. A script `pvc.py` which does the twitter search for polls and drops the results in a redis backend

The configuration for redis and twitter are in the env.sh file which sets environment variables.
These should be refactored out to a json config or something

Setup
=====

- clone the repo

- cd pvc-backend

- pipenv install
