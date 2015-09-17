# Overview

This charm deploys a simulator for DeviceHive. Once started, it will send random data to DeviceHive servers so you can demo without having to run hardware IoT devices. 

# Usage

Step by step instructions on using the charm:


    juju deploy dh-stream-simulator
    juju add-relation dh-stream-simulator devicehive

## Scale out Usage

If you add units of the simulator, it will create identifiers for each unit, making it easy to look at the dashboard and filter the data. 

## Known Limitations and Issues

N/A

# Configuration

* 


## Upstream Project Name

- Upstream website: https://github.com/tmatvienko/devicehive-spark-streaming-simulator
- Upstream bug tracker: https://github.com/tmatvienko/devicehive-spark-streaming-simulator


