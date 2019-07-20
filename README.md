# OnlineShopping
使用SSH框架设计的在线购物网站平台
目录
1.系统功能需求	1
2.数据库设计	2
3.非功能需求	2
4. 界面展示	2

本项目使用的是：eclipse+mysql+tomcat9
系统采用SSH框架，使用JSP生成表现层内容；使用Action作为控制器，接收客户请求，收集数据，实现业务层逻辑调用，并选择恰当视图对客户做出响应；使用JavaBean充当模型，用于数据的存储与提取。
1.系统功能需求
1.1“天天淘”前台功能结构图
1.2 “天天淘”后台功能结构图


2.数据库设计
	结合数据库课程的学习，自行根据信息需求完成数据库设计。
3.非功能需求
系统应通过过滤器实现用户登录与否的验证，除了浏览商品，其他操作都应该在用户登录的前提下才能进行
商品展示应实现分页展示
可以的话，能根据用户浏览的历史记录，设计出商品推荐算法，而不是在数据库里标注商品是否推荐。
4.界面展示
1）登录界面



2）登录后管理员界面

商品管理（增删改查）


会员管理（用户管理）

订单管理


3）登录后用户界面


购物车

我的订单

个人信息
