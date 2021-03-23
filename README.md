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


### Break down


3.23-3.27

| Category   | Detailed Description | Status | Possible Problems | 
| ------------- | ---------------------- | -- | -- |
| Scrape chudian small| 触点小表: 触点人群 30*1 | 已完成 ｜ 无 ｜
| Scrape kuaiche small | 快车小表: 快车创意 + 快车关键词 + 快车人群 30*3 |  已完成  ｜ 无 ｜
| Scrape zhanwei  | 展位小表：展位人群 30*1|  已完成 ｜  无  ｜
| Scrape jingxuan  | 京选： 关键词 + 搜索溢价人群 ：30*2| 已完成  ｜ 无｜
| Scrape haitou |  海投计划账户报表| 已完成 ｜ 无｜
| Scrape chudian large |  触点大表： 触点账户报表 + 触点账户推广创意报表 + 购物触点创意带sku| 带sku未完成｜ 无｜
| Scrape kuaiche large |  账户推广计划报表| 未完成｜无 ｜
| Scrape zhanwei large | 展位账户报表 |未完成 ｜  无｜


3.27-4.3

| Category   | Detailed Description | Status | Possible Problems | 
| ------------- | ---------------------- |--｜ -- ｜ 
| Scrape pinxiaobao| 品牌专区账户报表| 未完成｜ 无 ｜
| Scrape tmall super recommend | 超级推荐创意报表 + 超级推荐定向报表 | 未完成 ｜ 无｜ 
| Scrape fast pass | 直通车宝贝 +  直通车关键词| 未完成  ｜ 无｜
| Scrape diamond display  | 钻展创意 + 钻展定向报表|  未完成 ｜无 ｜



4.3 - 4.10

| Category      | Detailed Description | Status | Possible Problems | 
| ------------- | ---------------------- | -- | -- | 
| build data pipeline | 文件依赖路径处理|未完成 | chromedriver reset default download path问题 是否可行 |
| data cleaning to refomat data files | 数据清理 自动化过程： 拆分购物触点账户推广创意报表 +  删除最后一行改名： 快车账户推广计划报表 + 分拆两个品销宝流量包|未完成 | excel表格转成dataframe使用pandas能否做全部，df的格式导出之后是否保持一致，df读取spreadsheet✅ ， int防止转科学技术法是否保留|

4.10-4.17
优化
| Category      | Detailed Description | Status | Possible Problems | 
| ------------- | ---------------------- |-- | --| 
| （1）put script on server （如果登陆可以解决） | 代码放在服务器上跑| 未完成| 登陆问题的结束：1.简单滑块已解决 但是品销宝有人机识别 2. jd拼图滑块 3.输入手机验证码（无法解决）|
| (2) change download logic ｜ 下载逻辑变更->生成下载任务后立马去下载 ｜ 未完成 ｜ 和别人并行跑代码 可能会下错文件 更难察觉 ｜




