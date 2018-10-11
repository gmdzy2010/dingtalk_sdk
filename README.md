## 钉钉`非官方版`SDK

### 项目简介
--------------------  
本SDK非官方提供，但是鉴于本身代码简单，楼主三观正且能力有限（划重点），大可不必担心在SDK当中有什么恶意代码，不存在的   
钉钉官方只提供了java，node.js以及php版sdk，python版没有？？？，恰好最近业务需要，遂准备给钉钉写一整套SDK，不过钉钉的全部API有200+，测试是个大工程，其中很多业务用不上，所以先把基本的功能实现，后续的更新会把所有的功能陆陆续续补全，放出更新计划   
    
    
    
### 目前进度
--------------------  
项目的进度根据钉钉的官方文档结构编写

#### 用户认证

|接口名称|已完成/总数|  
|:---|:---|  
|用户认证|1/1|  
    
    
#### 通讯录管理

|接口名称|已完成/总数|  
|:---|:---|  
|通讯录权限范围|1/1|  
|用户管理|5/12|  
|部门管理|4/9|  
|角色管理||  
|外部联系人管理||  
|通讯录同步方案||  
    
    
#### 应用管理

|接口名称|已完成/总数|  
|:---|:---|  
|应用管理|0/6|  
    
    
#### 消息通知

|接口名称|已完成/总数|
|:---|:---|
|工作通知|3/3|
|群消息|5/5|
|普通消息|0/1|
|第三方个人应用发消息|0/1|
    
    
    
### 更新日志
--------------------  

#### 2018/10/11
1.修复接口调用属性`call_status`总为否的bug    
2.更新README英文版文档   

#### 2018/10/10
1.修改接口的调用的逻辑，现在需要在类实例化的时候提供关键字参数    
2.更新__doc__注释   
3.`NEW`新增群消息创建/修改/已读状态查询3个接口    
4.`NEW`新增工作通知消息发送状态/结果查询2个接口    



### 致谢
--------------------     
感谢钉钉的官方文档，感谢大家的关注与耐心，当然还有自己的辛勤付出:)  
