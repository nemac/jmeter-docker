# JMeter docker

## Requirements

- Java 8 Runtime

- JMeter 5.4

## Setup

- Use the GUI to record a test plan

- Export the test plan

- [Create a Remote Method Invocation keystore](https://jmeter.apache.org/usermanual/remote-test.html#setup_ssl) and place it in this directory (name it `rmi_keystore.jks`)

- `docker-compose build`

## Run it

- `docker-compose up`

### References

1. http://www.testautomationguru.com/jmeter-distributed-load-testing-using-docker/

