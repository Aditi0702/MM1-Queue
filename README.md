# MM1-Queue
Implemented a M/M/1 type queue system in Python, where:
 ```
 - arrivals and service times are exponentially distributed (implementing a poisson process)
- one unlimited queue FIFO
- one producer with configurable inter arrival time X (= 1/lambda)
- one consumer (service unit) with configurable service_time time Y (=1/mu)
- items remain in the queue until fully serviced by the consumer
```
