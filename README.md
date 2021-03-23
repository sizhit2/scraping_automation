# scraping_automation


## abstract
### Project Purpose
This app aims to scrape daily sales data from Chinese most popular e-commerce and prepare it for later importing to database and text analysis.
### Project Motivation
This app is to reduce the tedious workload of repeatedly downloading data from different sources on a daily basis.

## Technical Specification
Platform: Cross-platform app (React)

Programming Languages: Python for scraping.
                        JavaScript for rendering (Python for Flask should backend required)

Stylistic Conventions: JavaScript Style Guide

IDE: Visual Studio Code 

Tools/Interfaces: Web Application

Target Audience: people who need to do data collection

## Functional Specification
### Features

### Scope of the project
Limitation:
The project will subject to only scrap certain websites
Assumption:
The login will work without blocking from e-commerce websites

### Brief Timeline
Week 1: Enable Major Scraping functionalities on JD.com

Week 2: Enable Basic Data Cleaning

Week 3: Create UI for interaction

Week 4: Enable Login and put onto server to enable daily scraping


### Rubrics


Week 1 

| Category   | Detailed Description |
| ------------- | ---------------------- |
| Scrape chudian small| 触点小表: 触点人群 30*1|
| Scrape kuaiche small | 快车小表: 快车创意 + 快车关键词 + 快车人群 30*3 |  
| Scrape zhanwei  | 展位小表：展位人群 30*1|  
| Scrape jingxuan  | 京选： 关键词 + 搜索溢价人群 ：30*2|  
| Scrape haitou |  海投计划账户报表|
| Scrape chudian large |  触点大表： 触点账户报表 + 触点账户推广创意报表 + 购物触点创意带sku|
| Scrape kuaiche large |  账户推广计划报表|
| Scrape zhanwei large | 展位账户报表 |


Week 2 

| Category   | Detailed Description |
| ------------- | ---------------------- |
| Scrape pinxiaobao| 品牌专区账户报表|
| Scrape tmall super recommend | 超级推荐创意报表 + 超级推荐定向报表 |  
| Scrape fast pass | 直通车宝贝 +  直通车关键词|  
| Scrape diamond display  | 钻展创意 + 钻展定向报表|  



Week 3

| Category      | Detailed Description |
| ------------- | ---------------------- |
| build data pipeline | 文件依赖路径处理|
| data cleaning to refomat data files | 数据清理 自动化过程： 拆分购物触点账户推广创意报表 +  删除最后一行改名： 快车账户推广计划报表 + 分拆两个品销宝流量包|

Week 4

| Category      | Detailed Description |
| ------------- | ---------------------- |
| put script on server （如果登陆可以解决） | 代码放在服务器上跑|



