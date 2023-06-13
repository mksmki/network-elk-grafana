# NetFlow Test Data

[Link](https://open.scayle.es/dataset/netflow-data-with-sampling-for-test/resource/04cbe249-487a-4721-8d12-946ed93fb75d)

[Download URL](https://ss3.scayle.es/netflow-data/netflow_sampling_1000_001_test_new.csv)

### Grok pattern

```
%{NUMBER:unix_secs},%{NUMBER:unix_nsecs},%{NUMBER:sysuptime},%{IP:observer.ip},%{NUMBER:network.packets},%{NUMBER:source.bytes},%{NUMBER:first},%{NUMBER:last},%{NUMBER:engine_type},%{NUMBER:engine_id},%{IP:source.ip},%{IP:destination.ip},%{IP:nexthop},%{NUMBER:input},%{NUMBER:output},%{NUMBER:source.port},%{NUMBER:destination.port},%{NUMBER:prot},%{NUMBER:tos},%{NUMBER:tcp_flags},%{NUMBER:src_mask},%{NUMBER:dst_mask},%{NUMBER:src_as},%{NUMBER:dst_as},%{NUMBER:Label}
```
