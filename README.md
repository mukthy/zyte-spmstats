## Zyte-spmstats

It is a small python module for interacting with Zyte Smart Proxy Manager Stats API

### Documentation

[Zyte SPM Stats API Documentation](https://docs.zyte.com/smart-proxy-manager/stats.html)

### Installation

`pip install zyte-spmstats`

### Usage

`python -m zyte.spmstats <ORG-API> amazon.com 2022-06-15T18:50:00 2022-06-17T23:00`

Output:

`
      {
         "failed": 0,
         "clean": 29,
         "time_gte": "2022-06-10T18:55:00",
         "concurrency": 0,
         "domain": "amazon.com",
         "traffic": 3865060,
         "total_time": 1945
      },
`
