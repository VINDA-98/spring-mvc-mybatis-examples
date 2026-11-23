# SSM · Spring MVC 与 MyBatis 示例

[English](README.md)

Vinda 的 Java Web 练习项目，使用 Spring、Spring MVC、MyBatis 和 JSP。仓库包含一个学生业务示例和一个周报应用。

| 项目 | 可以查看的实现 |
| --- | --- |
| [`SSMTemplate`](SSMTemplate/) | 以学生查询为例，展示 Spring MVC 控制器、服务层和 MyBatis Mapper 的调用关系，并提供 JSP 页面示例。 |
| [`WeekLy`](WeekLy/) | 支持登录、提交和编辑周报、留言及 Excel 导出。 |

两个项目各有独立的 Maven POM，目标版本为 Java 8，均打包为 WAR。本地部署需要兼容的 Servlet 容器和 MySQL 数据库，并准备 Mapper XML 使用的数据表。数据库连接配置位于各项目的 `src/main/resources` 目录。
