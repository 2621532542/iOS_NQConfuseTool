# iOS_NQConfuseTool
iOS代码混淆(iOS_NQConfuseTool)是一款新一代运行在MAC OS平台的App、完美支持Objc和Swift项目代码的自动混淆、支持、文件名、修改资源文件、类名、方法名、属性名、添加混淆函数方法体、添加混淆属性、自动调用生成的混淆代码，功能强大而稳定。最重要的是完全免费。

# 前言
最近在看了不少的代码混淆， 就自己尝试的自己写了一个，


# MGTemplateEngine
MGTemplateEngine是mac平台下的一个代码生成器工具，根据模板和数据自动生成结果。它的使用很简单，语法比较灵活。

	NSString *name = @"zcj"
	
	//Hellow {{ name }}!
	//打印结果：Hellow zcj!
当然了，MGTemplateEngine也支持循环和条件判断，如下所示：

	NSArray *arr = [NSArray arrayWithObjects:
									@"matt", @"iain", @"neil", @"chris", @"steve", nil], @"guys"];
	
	//{% for dude in guys %}
		Current dude is {{ dude | uppercase }}
	{% /for %}
	//打印结果：Current dude is matt
	//Current dude is iain
	//Current dude is neil
	//Current dude is chris

	Is 1 less than 2? {% if 1 < 2 %} Yes! {% else %} No? {% /if %}
	//打印结果：Is 1 less than 2? Yes! 
	
MGTemplateEngine还提供更强大的规则和语法，详细信息请前往官方文档查询，地址：[https://github.com/mattgemmell/MGTemplateEngine](https://github.com/mattgemmell/MGTemplateEngine)。

	
# 总结
工具免费用，有问题可以留言联系，我看到及时更新。

掌握了代码混淆器的基本使用，我们就可以在遇到类似的场景，做出自己的自动处理方法。文档是copy[https://github.com/superzcj/ZCJTemplateTool](https://github.com/superzcj/ZCJTemplateTool)的，添加垃圾代码功能也是看的这位大佬的，没写过文档，短时间也懒的学，就先随便弄弄，多点赞，才有好的动力。 
