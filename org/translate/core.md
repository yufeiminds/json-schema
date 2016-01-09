## JSON Schema: 核心定义以及json-schema-core术语

### 摘要

JSON Schema 的媒体类型定义为「application/schema+json」 ，是一个对于 JSON 数据类型的基本格式定义。JSON Schema 提供了对一个给定的应用取得什么数据以及如何与之交互的约定。JSON Schema 想要为 JSON 数据定义验证、文档、超链接导航和交互控制。

### 这个备忘录的状态

这个互联网草案的提交完全遵从于 BCP 78 和 BCP 79的规定。

互联网草案是IETF（Internet Engineering Task Force, 互联网工程任务组）的工作文档。请注意，其他的团体也可能会贡献工作文档作为互联网草案（Internet-Drafts），当前的互联网草案列表在 http://datatracker.ietf.org/drafts/current/ 。

互联网草案是一个有最长六个月有效期并且可能被更新、替换或在任何时间被其他文档所淘汰的草案文档。这个材料并不适用于作为参考材料，抑或是与其他正在进行中的文档相比作为可引用的材料。

这个互联网草案将于2013年8月3日到期。

### 版权注意事项

Copyright(c) 2013 IETF 

…...

### 1. 序言

JSON Schema 是一个用于定义 JSON 数据结构的 JSON 媒体类型，JSON Schema 提供了对一个给定的应用取得什么数据以及如何与之交互的约定。JSON Schema 想要为 JSON 数据定义验证、文档、超链接导航和交互控制。

这份规格说明定义了 JSON Schema 核心术语和机制。