# Elixir Companies in China

> Inspired by https://github.com/doomspork/elixir-companies

在生产环境中使用 Elixir 的中国公司列表，按行业来归类：

#### 独立工作室
* [Ela Workshop](http://ela.build/) ([Github](https://github.com/ElaWorkshop)) - 生产环境中部署了 [HaloSir](https://github.com/HaloWordApp/halosir) 其他还有一些 [工具](https://github.com/ElaWorkshop/ex_loglite) 和实验性的项目。

#### SaaS
* [Strikingly](https://www.strikingly.com) ([Github](https://github.com/Strikingly)) - 用于高并发的 Analytics 数据查询服务。其中使用 Pheonix 和 GraphQL 做 API server，Rust 的 Native Extention 提高查询速度。

  [上线了](https://www.sxl.cn) 是 [Strikingly](https://www.strikingly.com/s/careers) 创建的专业易用的建站平台，无需任何编程和设计经验，任何人都可以在 15 分钟内创建一个功能强大网站，并且完美适配电脑、平板和手机等设备浏览的专业网站，今天，我们正在为超过 200 个国家和地区的用户持续创造价值、传递梦想。

#### 数据服务
* [LocalGravity AG](http://www.linkedin.com/company/localgravity?trk=top_nav_home) - 是一家零售数据选址咨询服务公司，成立于2012年，服务遍布中国、亚洲市场，中国分部有约135位员工。其拥有经验丰富的，结合本土与国际的专家团队，通过采集原始数据、建立零售地理信息平台、提供选址分析咨询服务; 协助连锁企业以科学的方式，更有效地进行全国门店网络选址规划，降低拓展风险、提升各门店效益。

  [LEAP] - 企业级零售数据分析平台。采用Elixir, Phoenix, Postgres, Docker实现API server。

#### 协作工具
* [Coding](https://coding.net)([Github](https://github.com/coding)) - Coding.net 是一个面向开发者的云端开发平台,提供 git 代码托管，免费的运行演示空间，代码质量分析，在线 Web IDE，项目管理，开发协作，基于云技术的软件外包，冒泡社交等功能。 为开发者提供技术讨论和开发，协作工具， Coding 极速的代码体验，让开发更简单。Coding 在 [WebIDE](https://ide.coding.net) 产品中使用了 Elixir 作为分布式的 sharding 服务。

#### 云计算
* [又拍云](https://www.upyun.com) ([GitHub](https://github.com/upyun)) - 又拍云以场景化 CDN 为核心业务，为客户提供云存储、云处理、云安全、流量营销等服务，帮助用户实现内容分发加速、产品研发加速、业务成长加速。目前主要应用 Elixir 于分布式文件存储相关服务，如存储代理，数据处理 ([Cafex](https://github.com/upyun/cafex))

#### 游戏公司
* [EJOY](https://ejoy.com)([Github](https://github.com/ejoy)) - 简悦成立于 2011 年，由网易前 COO 叮当、云风等人创建，以“专注于游戏、致力于为玩家创造快乐”为宗旨，是一家在游戏研发、运营方面具有领先优势的新兴企业。

  简悦平台组在游戏运营支撑业务中大量使用了 Elixir 进行开发，包括帐户模块，计费模块，用户信息收集展示，运营日志记录，游戏活动系统等。并开源了若干个项目
  * [MongoDB Driver](https://github.com/ejoy/elixir-mongo) 和配套的纯 C 实现的 [BSON 编解码器](https://github.com/sean-lin/elixir-cbson)
  * [Apk 第三方 SDK 注入器](https://github.com/sean-lin/ApkInjector)

### O2O 
* [住艺](http://www.zhuyihome.com/)([Github](https://github.com/ZhuyiHome)) 住艺，是康泰纳仕集团旗下精选设计师平台，是与国际权威家居生活杂志《安邸AD》关联的互联网消费升级第一品牌。
 
  住艺 Devs 使用 Elixir 及 Phoenix 开发对接装修设计师的 Web 系统，前端使用 [dva](https://github.com/dvajs/dva)，并会积极参与 Elixir 开源项目。我们很在意开发时工程师是否愉悦，因为我们坚信乐趣会带来更多创造性生产力。

## Contributing

欢迎通过 PR 添加、更新自己的公司或其他已知的公司。一些要求和建议：

1. 请尽量使用中文。但 Git commit message 最好用英文。
2. 请按名称拼音顺序排序（A-Z），行业也按拼音顺序排序。
3. 请给出公司名称和公司主页，甚至是公司的 GitHub organization 链接。
4. 可以加上公司简介，请尽量以一两句话概括。
5. 最好简单介绍一下该公司用 Elixir 做了什么，可以用一些链接来补充说明，比如相关技术博客、相关产品链接等等。
6. 请遵从 [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) 的要求。
7. 可以参考已有公司或者 [elixir-companies](https://github.com/doomspork/elixir-companies) 中公司的格式和内容。
