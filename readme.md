
#### Benchmarks

Performance comparison test of dropping 64 byte syn packet
![alt benchmarks](./docs/pk.png "iptables vs xdp")

#### Environment
* [Build development environment basied on VMs](./playground) (Recommended)
* [Build development environment basied on host](./docs/development_dependencies.md)


#### Get Started

Download directly from release tab or compile by yourself.
```
# Compile
$ make

# Get help
./xdp_acl -h

# Start (Inner web server will default listen on 0.0.0.0:9090).
./xdp_acl -D eth1 -S
```

#### Web console

![alt web console](./docs/console.png "web console")

