# IIX Community List #
## Community received from peers ##
| No | Action | Standard | Extended | Large |
| -- | ------ | -------- | -------- | ----- |
| 1 | Do not advertise to peer-as | 0:peer-as | rt:0:peer-as | 7597:0:peer-as |
| 2 | Advertise to peer-as | 7597:peer-as | rt:7597:peer-as | 7597:1:peer-as |
| 3 | Do not advertise to any peer | 0:7597 | rt:0:7597 | 7597:0:0 |
|-- |-- |-- |-- |-- |
| 4 | Prepend 1 time  to peer-as | 65001:peer-as | rt:65001:peer-as | 7597:65001:peer-as |
| 5 | Prepend 2 times to peer-as | 65002:peer-as | rt:65002:peer-as | 7597:65002:peer-as |
| 6 | Prepend 3 times to peer-as | 65003:peer-as | rt:65003:peer-as | 7597:65003:peer-as |
|-- |-- |-- |-- |-- |
| 7 | Blackhole | 65535:666 | | |
