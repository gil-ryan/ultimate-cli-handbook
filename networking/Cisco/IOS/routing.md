# Routing Command

# Distribute List

```
access-list 10 permit 10.10.11.0 0.0.0.255
access-list 10 permit 10.10.12.0 0.0.0.255
router ospf 10
redistribute eigrp 10
distribute-list 10 out eigrp 10
```
