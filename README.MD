```shell
ab -c 5 -n 500 http://127.0.0.1:9080/service-a/work
ab -c 5 -n 500 http://127.0.0.1:9080/service-a/error
ab -c 5 -n 500 http://127.0.0.1:9080/service-b/work
ab -c 5 -n 500 http://127.0.0.1:9080/service-b/error
```