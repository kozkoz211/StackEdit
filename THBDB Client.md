# THBDB


## getKeys

select all keys from bdb


### UML diagrams

```mermaid
sequenceDiagram
client ->> server: getKeys(
server-->> bdb: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MzMxMTE1ODEsLTEzMzQxMjU3ODhdfQ
==
-->