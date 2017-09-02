---
order: 0
title:
  zh-CN: 进度条
  en-US: Progress bar
---

## zh-CN

标准的进度条。

## en-US

A standard progress bar.

````jsx
import { Progress } from 'antd';
"itemStyle": {
                "normal": {
                    "color": "#5886f0",
                    "borderColor": new echarts.graphic.LinearGradient(0, 0, 0, 1, [{
                        offset: 0,
                        color: '#00a2ff'
                    }, {
                        offset: 1,
                        color: '#70ffac'
                    }]),
ReactDOM.render(
  <div>
    <Progress percent={30} />
    <Progress percent={50} status="active" />
    <Progress percent={70} status="exception" />
    <Progress percent={100} />
    <Progress percent={50} showInfo={false} />
  </div>
, mountNode);
````
