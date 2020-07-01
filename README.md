# QATraderBroker
`ctpbee` 实盘对接`QA`期货实盘 组件 

使用tornado 技术栈


此后ctpbee的所有实盘接口均可通过此项目对接到QA的策略执行中去

 > Have a nice day 
 
 ## 执行过程
 
 发单: QAStrategy --> <OrderRoute> ---> QATraderBroker ---> ctpbee实盘接口 --- > 实盘服务器
 
 回报: 实盘服务器 --> 回报更新到ctpbee本地 ---> 推送到OrderRoute ----> 更新QAStrategy 
 
 
 
 > ps: README编程  ～～～
