# apiJFrame-pawnluo

apiFrame
2019年4月9日
1.接口调通支持批量请求，响应，数据回写

2019年4月10日
1.使用maven-surefire-plugin插件使脚本脱离eclipse运行使用maven命令运行。
2.调试实例base64转图片&图片插入表格。
3.新增表字段assertresult，用于断言用例是否通过

2019年4月11日
1.RequestData请求数据字段，无需去除空格、回车、制表符格式化，支持粘贴来源的json数据格式
2.新增AssertResult字段，用于链接外部base64解密图片（通过点击表格内容，打开外部图片）

2019年4月15日
添加log4j日志

修改batchWrite()，解除代码耦合，取消sheetName传参
修改excelUtils类，实现一次性回写多个sheet内容

取消log4j日志

2019年4月16日
添加HttpPostWithXml方法，支持xml数据格式请求。
新建dataprovider类，代码结构优化，减少线性代码

2019年4月17日
引入FastJson类
处理LabelImage字段返回的一长串Base64响应报文
替换为固定文本,并写出为图片保存在本地
新增字段测试标题

2019年7月12日下午12:35:28 引入hibernate ORM框架
 
2019年7月22日下午5:37:10 引入钉钉SDK

2019年8月2日10:28:40 重新设计WriteCollection接口,实现其子类PrintLabelBean,CancelLabelBean

2019年8月2日10:24:44  引入Extentreport测试报告

2019年8月8日21:09:20 完成脚本-当天订单批量取消

2020年4月26日 09:36:28 移除hibernate及sqlserver驱动，移除钉钉机器人，调整工程目录


                                        power by:pawnluo