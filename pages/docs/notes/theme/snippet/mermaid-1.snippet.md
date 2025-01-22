---
title: mermaid-1.snippet
createTime: 2025/01/09 19:35:06
permalink: /article/h1t0gega/
---
````md
```mermaid
---
title: Flowchart
---
flowchart TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end
    one --> two
    three --> two
    two --> c2
```
````
