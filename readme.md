# Golang Windows Service Starter App

Provides a way to quickly pull down the files needed to get you going quickly. Copied from [here](https://github.com/golang/sys/tree/master/windows/svc/example)

## How do I run the service?

Download the code.

Build it:
> go build

Move the exe to wherever you want the app to live.
> ./windowsservice.exe install
> ./windowsservice.exe start

You should then see the service in task manager under the services tab as running.