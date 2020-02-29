﻿# ImomoeAPI 介绍
## 实现功能

- [x] 获取每日更新列表
- [x] 获取不同类型列表

## 优点

简单, 更新速度快...

## 使用方法

| 函数  | 返回值  | 详细 |
| :------------ |:---------------:| :-----:|
| search(keyword, pageIndex) | 结果总数 | 搜索一个关键字返回搜索结果总数以及搜索结果SakuraBangumi[] |
| getByTheme(themeType, pageIndex) | 结果总数 | 搜索一个主题返回搜索结果总数以及搜索结果SakuraBangumi[] |
| searchResult() | SakuraBangumi[] | 获得上述两种方法得到的最后一次搜索结果 |
| getDailyUpdate(weekIndex) | SakuraBangumi[] | 获取每日更新列表 |
| SakuraBangumi.loadMoreDetail() | SakuraBangumi | 对单条搜索结果进行更多数据加载 |
| SakuraBangumi.getPlaySource(0) | String | 对单条搜索结果进行视频地址获取 |

## 其他说明

仅作测试, 请勿用于其他用途
