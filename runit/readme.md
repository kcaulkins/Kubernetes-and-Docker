# Runit example
This is basic image which will copy `./run_test` to `/etc/sv/test` on the container, then start the service.

This can also be found on docker hub here: https://hub.docker.com/repository/docker/keithcaulkins/runit-example

Example of a simple `run_test` script to show it functioning:

```
#!/bin/sh

while true
do 
    echo "test"
    sleep 5
done
```
