# SSM · Spring MVC and MyBatis Examples

[简体中文](README.zh-CN.md)

Two Java web exercises built with Spring, Spring MVC, MyBatis and JSP. A student lookup demonstrates the application layers, and a weekly-report application illustrates how they fit together in a larger workflow.

| Project | What to explore |
| --- | --- |
| [`SSMTemplate`](SSMTemplate/) | A student lookup example with a Spring MVC controller, service, and MyBatis mapper, plus sample JSP views. |
| [`WeekLy`](WeekLy/) | A weekly-report application with sign-in, report submission and editing, messages, and Excel exports. |

Both projects have their own Maven POM, target Java 8, and package as WAR files. For a local deployment, each app needs a compatible servlet container and a MySQL database with the tables expected by its mapper XML. The database configuration belongs in each app's `src/main/resources` directory.
