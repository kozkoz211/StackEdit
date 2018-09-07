# THBDB


## getKeysByPosition

select all keys from bdb


### UML diagrams

```mermaid
sequenceDiagram
client ->> server: getKeysByPosition(i32 position, i32 size)

Note right of client: position is zero-origin

server ->> bdb: getKeysByPosition(1:i32 position, 2:i32  size) throws (1:InvalidOperation exp)


bdb ->> server: 
server ->> server: 
server ->> client: 



```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMDIwNjA2OCwxNDc5MTU3Njk0LC0xOD
I4ODA0MTU5XX0=
-->