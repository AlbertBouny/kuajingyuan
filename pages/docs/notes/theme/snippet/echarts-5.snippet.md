---
title: echarts-5.snippet
createTime: 2025/01/09 19:35:06
permalink: /article/apwys60a/
---
````md
::: echarts Two Value-Axes in Polar
```js
const data = []

for (let i = 0; i <= 100; i++) {
  const theta = (i / 100) * 360
  const r = 5 * (1 + Math.sin((theta / 180) * Math.PI))
  data.push([r, theta])
}

const height = 450

const option = {
  legend: {
    data: ['line'],
  },
  polar: {},
  tooltip: {
    trigger: 'axis',
    axisPointer: {
      type: 'cross',
    },
  },
  angleAxis: {
    type: 'value',
    startAngle: 0,
  },
  radiusAxis: {},
  series: [
    {
      coordinateSystem: 'polar',
      name: 'line',
      type: 'line',
      data,
    },
  ],
}
```
:::
````
