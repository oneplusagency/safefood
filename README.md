# OrgServer

**Data Server** scaffold for all kinds of **Organizations**, built on [Strapi][1]
with the **Operation Experience** of [freeCodeCamp ChengDu community][2] & [KaiYuanShe][3].

## Learning

https://tech-query.me/development/headless-cms-strapi/

## Data Structure

### Model

|  Collection  |          Usage           |                         Remark                          |
| :----------: | :----------------------: | :-----------------------------------------------------: |
|   Category   |  Content Classification  |        associated with a variety of Content data        |
|   Comment    |     Content Comment      |        associated with a variety of Content data        |
|   Account    |        In/Outcome        |             Sponsorship, Travel or Purchase             |
|   Property   |         Supplies         |                 Equipment or Souvenirs                  |
|     User     | external registered User |                     not Admin users                     |
| Organization |  external Organization   | Company, Open-source Community, non-profit Organization |
|    Place     |                          |                       in/outdoor                        |
|   Project    |                          |           Open source, Public Welfare project           |
|     Task     |                          |                                                         |
| Contribution |    Task Contribution     |                                                         |
|   Program    |     Activity Section     |              Lectures, Workshops or Booths              |
|   Activity   |                          |        various Small, Medium or Large activities        |
| Partnership  |                          |               Cooperation or Sponsorship                |
|  Evaluation  |                          |  Evaluation of Task contribution and Activity sections  |

### Component

|  Name  | Category |         Usage          |
| :----: | :------: | :--------------------: |
| Period |   Date   |       Time Range       |
| Goods  | Supplies | Equipment or Souvenirs |

[1]: https://strapi.io/
[2]: https://fcc-cd.dev/
[3]: https://kaiyuanshe.cn/
