<h2>4.1 逐渐取代自动配置</h2>

自动配置是非侵入性的。在任何时候，您都可以定义自己的配置，以替换自动配置的特定部分。例如，如果您添加自己的```DataSource``` bean，则默认的嵌入式数据库支持将不被考虑。

如果需要查看当前应用启动了哪些自动配置项，请使用```--debug```开关启动应用程序。这将为核心日志开启debug日志级别，并将自动配置相关的日志输出到控制台。