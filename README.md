# Scott Portfolio Data

独立数据仓库，存储监控数据和状态信息。

## 用途

此仓库用于存储 scott-portfolio 的监控数据，与主仓库分离，实现逻辑与数据分离。

## 数据文件

- `status-monitor/cognitive-data.json` - 当前认知负载状态
- `status-monitor/cognitive-history.jsonl` - 认知负载历史记录

## 数据来源

数据由认知监控系统自动推送更新。

## 访问方式

通过 GitHub raw 文件服务访问：
- https://raw.githubusercontent.com/hiyaScott/scott-portfolio-data/main/status-monitor/cognitive-data.json
- https://raw.githubusercontent.com/hiyaScott/scott-portfolio-data/main/status-monitor/cognitive-history.jsonl
