# 系统截图
	![image](https://github.com/1752325542/daifu/blob/master/doc/43B65516-391A-4BAF-A53C-BBFD8AD4E760.png)

# 系统说明
	1. 	同一账户日限额20万
	2.	同一账户每日最高交易15笔
	3.	支持谷歌验证器登录
	4.	单笔交易最低10元，最高49999元
	5.	支持商户IP白名单

# 系统功能
	1.	应用管理: 同时支持公司多个业务系统对接。
	2.	商户管理: 支持商户入驻，商户需要向平台方提供相关的资料备案。
	3.	渠道管理: 支持微信、支付宝、银联、京东支付等多种渠道。
	4.	账户管理: 渠道账户管理，支持共享账户（个人商户）及自有账户。
	5.	支付下单: 生成预支付订单、提供退款服务。
	6.	通知模块: 处理第三方支付渠道的异步通知，并将处理结果同步至业务系统。
	7.	对账处理: 实现支付系统的交易数据与第三方支付渠道交易明细的自动核对（通常T+1），确保交易数据的准确性和一致性。
	8.	商户清算: 计算收款交易中商户的应收与支付系统收益。
	9.	商户结算: 根据清算结果，将资金划拨至商户对应的资金帐户中。
  
  
# API接口
	1.	单笔代付接口
	2.	批量代付接口
	3.	交易查询接口
	4.	余额查询接口
	5.	打款通知回调接口
  
# 开发技术
	1.	Golang+CentOS+Postgres+Nginx+ReactJS
	2. 	商户API对接文档见doc/dev.html
	3. 	平台数据采用RSA2加密传输（同支付宝业务流程一样）

# Bug修复

	Bug反馈邮箱：1752325542@qq.com	

