#### v0.4.2 2018/12/04
`NEW!`新增sns access_token获取接口  
`NEW!`新增根据unionid获取userid的接口  
增加每次不同接口调用时的日志写入记录  

-------------------------------------------------------------------------------

#### v0.4.1 2018/12/03
1.`NEW!`新增持久授权码/openid/unionid获取接口  
2.`NEW!`新增用户信息获取接口，为扫码登陆做准备  
3.增加新增功能的本地测试，调试当中  

-------------------------------------------------------------------------------

#### v0.4.0 2018/11/28
1.增加系统化的测试模块  
2.测试接口认证模块  

-------------------------------------------------------------------------------

#### v0.3.1 2018/11/03
1.pytest测试脚本未通过，正在寻找原因  
2.初步将测试放在travis CI，写了配置文件与测试脚本

-------------------------------------------------------------------------------

#### v0.3.0 2018/10/20
1.更新repositories结构，结构更合理

-------------------------------------------------------------------------------

#### v0.2.5 2018/10/16
1.更新README.md文档至pypi

-------------------------------------------------------------------------------

#### v0.2.4 2018/10/15
1.更新所有类描述__doc__      
2.为目前版本的SDK写了所有文档

-------------------------------------------------------------------------------

#### v0.2.3 2018/10/12
1.更新`DeptsRequest`模块按部门名称获取id的方法`get_depts`      
2.针对生产使用写了一个简单的[使用示例](https://github.com/gmdzy2010/dingtalk_sdk_gmdzy2010/blob/master/doc_for_bms.md)  

-------------------------------------------------------------------------------

#### v0.2.2 2018/10/11
1.已发布至pypi，包名称`dingtalk-sdk-gmdzy2010`      
2.修复0.2.1发布版本settings模块导入的bug       

-------------------------------------------------------------------------------

#### v0.2.1 2018/10/11
1.修复接口调用属性`call_status`总为否的bug    
2.更新README英文版文档   

-------------------------------------------------------------------------------

#### v0.2.0 2018/10/10
1.修改接口的调用的逻辑，现在需要在类实例化的时候提供关键字参数    
2.完善__doc__注释   
3.`NEW!`新增群消息创建/修改/已读状态查询    
4.`NEW!`新增工作通知消息发送状态/结果查询    