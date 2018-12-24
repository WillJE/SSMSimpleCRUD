>项目来源于尚硅谷的SSM整合项目。

### 项目简介
使用ssm框架进行整合，实现一个小的项目，对员工信息的增删改查。

### 技术栈
1、基础框架-ssm(SpringMVC+Spring+MyBatis)
2、数据库-MySQL
3、前端框架-bootstrap快速搭建简单美观的界面
4、项目的依赖管理-Maven
5、分页-pagehelper
6、逆向工程-MyBatis Generator

### 功能点
1、数据校验（jquery前端校验+JSR303后端校验）
2、大量使用ajax技术，如在该项目中的用户名校验、编辑、单个删除、多个删除
3、Rest风格的URL;使用HTTP协议请求方式的动词，来表示对资源的操作（GET（查询）,POST（新增）,PUT（修改）,DELETE（删除））。

### 功能实现

#### 查询
1、访问index.jsp页面
2、index.jsp页面发送出查询员工列表请求
3、EmployeeController来接收请求，查出员工数据
4、来到list.jsp页面进行展示

#### 修改
1、点击编辑
2、弹出用户修改的模态框（显示用户信息）
3、点击更新，完成用户修改

#### 增加
1、在index.jsp页面点击"新增"
2、弹出新增对话框
3、去数据库查询部门列表，显示在对话框中
4、用户输入数据，并进行校验
（jquery前端校验，ajax用户名重复校验，重要数据（后端校验（JSR303），唯一约束）;
5、完成保存

#### 删除
1、单个删除

#### API
- /emp/{id} GET查询员工
- /emp      POST保存员工
- /emp/{id} PUT修改员工
- /emp/{id} DELETE 删除员工

### 项目截图

**首页**

![首页](https://github.com/WillJE/SSMSimpleCRUD/blob/master/screenshot/%E9%A6%96%E9%A1%B5.png)

**新增员工**

![新增员工](https://github.com/WillJE/SSMSimpleCRUD/blob/master/screenshot/%E5%91%98%E5%B7%A5%E6%B7%BB%E5%8A%A0.png)

