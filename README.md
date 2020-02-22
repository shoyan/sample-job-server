# sample-job-server

## Install

```
$ git clone https://github.com/shoyan/sample-job-server.git
$ cd sample-job-server
$ pip install schedule
```

## Run

```
$ python job.py
$ python que_server.py
$ curl http://127.0.0.1:5000/add -XPOST -d "body=hello"
=> job.py
hello
```
