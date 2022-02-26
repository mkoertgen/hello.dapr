# hello.dapr

## Getting Started

Having [dapr-cli installed](https://docs.dapr.io/getting-started/install-dapr-cli/)

```shell
$ dapr init
Making the jump to hyperspace...
Installing runtime version 1.6.0

$ dapr run -- dotnet run --project DaprCounter
Starting Dapr with id Seerfog-Raccoon. HTTP Port: 51046. gRPC Port: 51047
Checking if Dapr sidecar is listening on HTTP port 51046
time="2022-02-26T03:00:04.4882967+01:00" level=info msg="starting Dapr Runtime -- version 1.6.0 -- commit 4bb25fab444c4f1a1bf0ffd74293dbd4fdcea580" app_id=Seerfog-Raccoon instance=frodo scope=dapr.runtime type=log ver=1.6.0
time="2022-02-26T03:00:04.4893454+01:00" level=info msg="log level set to: info" app_id=Seerfog-Raccoon instance=frodo scope=dapr.runtime type=log ver=1.6.0
time="2022-02-26T03:00:04.489871+01:00" level=info msg="metrics server started on :51048/" app_id=Seerfog-Raccoon instance=frodo scope=dapr.metrics type=log ver=1.6.0
...
== APP == Counter = 0
== APP == Counter = 1
time="2022-02-26T03:00:08.34236+01:00" level=info msg="Shutting down actor" app_id=Seerfog-Raccoon instance=frodo scope=dapr.runtime type=log ver=1.6.0

terminated signal received: shutting down
Exited Dapr successfully
Exited App successfully
```

## References

See

- [Get started with Dapr](https://docs.microsoft.com/en-us/dotnet/architecture/dapr-for-net-developers/getting-started)
