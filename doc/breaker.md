# 熔断机制设计

## 设计目的
* 依赖的服务出现大规模故障时，调用方应该尽可能少调用，降低故障服务的压力，使之尽快恢复服务