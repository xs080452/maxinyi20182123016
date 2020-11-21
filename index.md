
## 小组作业

 ## 信息 
      —— 姓名：马欣怡
      —— 学号：20182123016
      —— 负责部分：project部分用例图及文字说明

 ## 用例图
 ![image](https://github.com/xs080452/maxinyi20182123016.github.io/blob/main/12.png)

 ## 文字说明
     —— 用例名称：project
     —— 用例说明:Adminstrator可以在登录后进行创建项目、编辑项目、复制项目、删除
                 项目、项目自动化、设置等操作	 
                 User可以在登录后进行创建项目、编辑项目、复制项目、删除项目、项
                 目自动化、设置等操作

      —— 参与者：Adminstrator、User	
      —— 元素：Create projects, edit projects, copy projects, delete projects, 
               automate projects,  set up	
      —— 关系：Adminstrator对于Create projects, edit projects, copy projects, 
               delete projects, automate projects,  set up	是依赖关系
               User对于Create projects, edit projects, copy projects, delete 
               projects, automate projects,  set up是依赖关系
       —— 建模思路:
               1 .Administrator 登录Github进入仓库之后可以进行projects操作，所
                  以project和Administrator构成依赖关系。
               2. User 登录Github进入仓库之后可以进行projects操作，所以project
                  和User构成依赖关系。
               3.Administrator 登录Github进入仓库之后进入projects可以进行Create
                 projects, edit projects, copy projects, delete projects, automate 
                 projects, set up操作，所有这些选项和project构成扩展关系。
               4.User登录Github进入仓库之后进入projects可以进行 Create projects, edit 
                  projects, copy projects, delete projects, automate projects,  set up
                  操作，所有这些选项和project构成扩展关系。
