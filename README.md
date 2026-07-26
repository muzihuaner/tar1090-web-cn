# tar1090-web-cn

[tar1090](https://github.com/wiedehopf/tar1090) 网页的中文汉化版 — 一个基于 Web 的 ADS-B 飞机追踪界面。

## 功能

- 实时显示 ADS-B 飞机数据（位置、高度、速度、航向等）
- 支持 MLAT / Mode S / TIS-B 多种数据源
- 历史轨迹回放
- 点击呼号（应答机编码下方）查询航班信息，支持：
  - FlightRadar24
  - FlightAware
  - Flightera
  - PlaneFinder
  - ADSBExchange
  - Variflight
- 完整的汉化界面

## 使用

将 `html-webroot/` 部署到任意 Web 服务器即可使用。需要后端提供 tar1090 数据接口。

Docker 部署示例

```
docker cp /root/html-webroot tar1090:/usr/local/share/tar1090/

```

## 版本

基于 tar1090 v3.14.1815
