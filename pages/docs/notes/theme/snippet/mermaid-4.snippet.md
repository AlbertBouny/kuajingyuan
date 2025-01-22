---
title: mermaid-4.snippet
createTime: 2025/01/09 19:35:06
permalink: /article/x2mvo55x/
---
````md
```state Check if n is negative

state if_state <<choice>>
[*] --> IsPositive
IsPositive --> if_state
if_state --> False: if n < 0
if_state --> True : if n >= 0
```
````
