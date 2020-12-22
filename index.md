
## 小组第一次作业

## 信息 
      —— 姓名：马欣怡
      —— 学号：20182123016
      —— 负责部分：project部分用例图及文字说明

## 用例图
 ![image](https://github.com/xs080452/maxinyi20182123016.github.io/blob/main/er.png)

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

## 小组第二次作业
## 负责部分题目内容
    —— 2.学院公众号中，成绩查询模块可以很方便地使在校学生查询到期末考试成绩，特别是老师将期
         末成绩提交后，该模块会以弹窗的方式将信息通知到学生，问题：请根据滇池学院微信公众号
         中，学生成绩查询模块的功能，对该模块进行小组讨论分析，对该功能的类图中以下元素进行
         必要说明：
## 作业内容：
   ###  1.该功能一共应该包含哪几个类	
         答： 编号   	类名称           	类说明         
               1	    学生类   	用于描述查询成绩学生的基本信息
               2	    学期     筛选类	按学期数管理每学期科目成绩
               3	    科目类  	 按科目名称管理成绩
               4	    学分类	   每一科目的学分信息
               5	    成绩类   	每一科目的成绩信息
   ###  2.每个类的属性，方法应该是什么，有什么作用，权限该是什么	
          学生类：
                 属性	      
                           姓名	    登录系统学生的姓名，类型为字符串String，Private属性
                  	         学号	    登录登录系统学生的学号，类型为字符串String，Private属性
                           	班级    	登录系统学生所在班级，类型为字符串String，Private属性
                        	   分院	    登录系统学生所在分院，类型为字符串String，Private属性
                 方法   	   
                           登录	    登录成绩查询系统
	                           查询    	查询该学生相关成绩信息
	                           打印    	打印该学生相关成绩信息
         ===========================================================================================
          学期筛选类：
                 属性   	   
                           18至19学年上学期	  在此学期内的成绩信息，类型为字符串String，Private属性
                           	18至19学年上学期	  在此学期内的成绩信息，类型为字符串String，Private属性
                           	19至20学年上学期	  在此学期内的成绩信息，类型为字符串String，Private属性
                           	19至20学年下学期  	在此学期内的成绩信息，类型为字符串String，Private属性
                        	   全部数据	          在校期间内的所有成绩信息，类型为字符串String，Private属性
                 方法	      
                           查询	              查询在该期间内的相关成绩信息
	                           打印    	          打印该期间内的相关成绩信息
         ============================================================================================
         科目：
                 属性      
                           科目名称	      类型为字符串String，Private属性
	                           学科          类型	此科目的学科类型，类型为字符串String，Private属性
                 方法      	
                           打印	          打印此科目的相关成绩
	                           查询	          查询此科目的相关成绩
         =============================================================================================
         成绩类：
                 属性	      
                           期末成绩       	类型为字符串String，Private属性
	                           平时成绩       	类型为字符串String，Private属性
                           	作业成绩	       类型为字符串String，Private属性
                           	期中成绩	       类型为字符串String，Private属性
                           	成绩类型	       类型为字符串String，Private属性
	                           总评成绩       	类型为字符串String，Private属性
                 方法      	
                           查询	           查询该成绩
                           	打印	           打印该成绩
         =============================================================================================
         学分类：
                 属性	      
                           应修学分       	该科目应得学分，类型为字符串String，Private属性
	                           实修学分	       该科目实际所得学分，类型为字符串String，Private属性
	                           绩点	           该科目绩点，类型为字符串String，Private属性
	                           学分绩         	该科目的学分绩，类型为字符串String，Private属性
                 方法      
                           查询	           查询该科目学分信息
	                           打印           	打印该科目学分信息

### 3.类之间分别有什么关系	
           答：用户类与成绩类：依赖关系   用户类与系统类：依赖关系   成绩类和系统类：关联关系
### 4.使用 staruml 画出该功能模块
 ![image](https://github.com/xs080452/maxinyi20182123016.github.io/blob/gh-pages/QQ%E5%9B%BE%E7%89%8720201222192433.png)
    
         
             
