

```
 watch -c juju status --relations --color
```

```bash
Model    Controller  Cloud/Region         Version  SLA          Timestamp
default  localhost   localhost/localhost  2.6.5    unsupported  17:50:51+08:00

App         Version  Status  Scale  Charm       Store  Rev  OS      Notes
floodlight           active      1  floodlight  local    4  ubuntu  

Unit           Workload  Agent      Machine  Public address  Ports  Message
floodlight/5*  active    executing  5        10.153.185.252         (install) Running floodlight

Machine  State    DNS             Inst id        Series  AZ  Message
5        started  10.153.185.252  juju-89f080-5  xenial      Running
````
