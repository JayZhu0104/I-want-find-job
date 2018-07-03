# 需求分析
![img](/就业信息管理系统需求.png)
---
# 进度管理

时间 | 强哥 | 俊杰 | 科杰 | 志哥 | 备注
---|---|---|---|---|--- 
周一 | 软件需求说明书 | ... | ... | ... |共同完成管理员需求说明书，强哥俊杰负责企业，科杰志哥负责学生
完成度|完成
周二 | 上午数据流图，下午ER图



# 软件需求说明
---
## 管理员功能说明
- 企业模块管理
    - 对企业资质认证及信息修改请求的审核
    - 对企业列表信息进行查改
    - 对企业进行删除
    - 对企业发布招聘信息进行的查看及审核
- 学生模块管理
    - 对学生的信息批量导入
    - 对学生的注册登记信息审核
    - 对学生相关信息进行查看（按照学校专业班级查询）
    - 对学生的就业信息的登记处理
- 管理员自身管理
    - 对自身信息的修改


## 学生功能说明
- 注册功能
- 申请修改自身个人信息，包括提交个人认证
- 填写求职意向并发放自身求职简历
- 查询企业招聘信息
- 向对应企业发送求职简历
- 登记就业信息

### 学生用例图
![学生用例图](/学生用例图.png)

## 企业功能说明
- 可以用手机号进行注册
- 企业基本信息的填写，包括企业名称、企业地址、企业简介、联系方式、企业的资质证明，并等待管理员审核。
- 企业招聘信息的填写，包括具体的岗位以及相关的要求
- 对企业的基本信息、招聘信息的修改，并等待管理员审核。
- 企业可以查看申请岗位人员简历信息

## 游客功能说明
- 浏览企业的招聘信息

