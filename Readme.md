
This demo uses `docker-compose` and by default runs against the
`otel/opentelemetry-collector:0.68.0` image. To run the demo, switch
to the `demo` folder and run:

```shell
docker compose up -d
```



Notes:

- Generate load by hiting url: http://localhost:7080/hello
```shell
repeat 15 curl -i http://localhost:7080/hello
```

To clean up any docker container from the demo run `docker-compose down` from
the `demo` folder.

