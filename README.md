### 基于Spring boot 的 CTF 平台 ###


###功能实现 ###

#### 基本功能 ####

- 登录
    - 表单
- 注册
    - 填写表单（普通）
    - 绑定github
- 用户信息
    - 更改密码
        - 表单提交
- 题目信息
    - 展示
        - 写题目接口
- 积分榜
    - 展示
        - 写积分榜接口 
- 公告
    - 展示
        - 写公告接口
- 后台入口(根据用户ID自动显示入口)
    - 题目列表
        - 写接口
    - 题目详情
        - 展示
        - 修改(增删改查)
    - 人员列表
        - 写接口
        - 查询
    - 人员详情
        - 展示
        - 修改(增删改，封禁，设为管理员)
 
#### 数据库 ####

- 用户
    - ID
    - 昵称
    - 邮箱
    - 当前密码
    - 所属队伍ID
    - 联系方式
    - 是否封禁
    - 是否为管理员
    - 是否为超级管理员
    
- 赛题
    - ID
    - 标题
    - 内容
    - 分值
    - 所属类别
    - Flag
    - 发布时间
    - 结束时间
    - 被解次数
    
- 队伍
    - ID
    - 队伍名称
    - 队伍Token
    - 队伍成员ID(即用户ID)
    - 已解赛题ID，解题时间;
    - 总分数
    
- 公告
    - ID
    - 标题
    - 内容

#### 组织结构


#### 技术选型
| 技术         |  说明         | 官网                  |
|-------------|---------------|----------------------|
| Spring Boot |               |                      |
| Mybatis      |              |                      |
|  MySql      |               |                      |







    
    

