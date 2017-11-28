# mavendemo-spring
1.基于https://github.com/a304407493/mavendemo-web.git<br/>
2.maven骨架的spring项目<br/>
3.pom增加maven的sql插件<br/>
	执行方式：<br/>
		3.1.在mysql中创建yourdb的数据库<br/>
		3.2.执行命令mvn test（sql:execute不起作用）<br/>
			注：3.2.1.记得修改pom.xml的配置文件 3.2.2.创建yourdb的数据库<br/>
4.pom增加mybatis<br/>
5.pom增加spring3+调度任务quartz<br/>
6.pom增加spring本身的调度任务<br/>
7.pom增加quartz支持集群和多种方式配置<br/>
8.pom增加支持druid，修改的druid本地数据库配置错误的地方<br/>
