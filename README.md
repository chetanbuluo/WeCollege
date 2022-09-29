

# 项目介绍


- 本小程序包括学校公告,服务通知,校园新闻,校园风光,校园活动,校历,课程表,失物招领,迎新服务,问卷调查,空闲教室,借阅报告,课堂印象等功能模块！
- 在这里，学生可以查看考勤，成绩，课表，校园活动等一系列基本应用，为丰富学生的校园生活，学生可以通过互动模块进行社交
- 创建表白主题：为便捷学生生活，学生可以失物招领，维修申请等解决校园生活问题；为解决学生课后疑问，提供课后问答模块
- 为大学老师技工快捷查找休闲教室，智能办公，管理学生，查询学生成绩，考勤，解答学生课后问题等一系列服务。

![image](https://user-images.githubusercontent.com/114638578/192943865-5a787150-3c58-4dc3-adf7-5eae40362afd.png)

# 功能说明
![image](https://user-images.githubusercontent.com/114638578/192943878-f2c720c0-0d32-41e6-b018-636fa4e7cc43.png)


# 技术运用

- 项目使用微信小程序平台进行开发。
- 使用腾讯云开发技术，免费资源配额，无需域名和服务器即可搭建。
- 小程序本身的即用即走，适合小工具的使用场景，也适合程序的开发。

# 项目效果截图
![image](https://user-images.githubusercontent.com/114638578/192943893-a07475a0-c821-45b5-9c1a-01b5d728a912.png)
![image](https://user-images.githubusercontent.com/114638578/192943899-8791f1fd-600c-495d-b111-9be28987045f.png)
![image](https://user-images.githubusercontent.com/114638578/192943903-5f7d9936-cc38-4cc9-ad87-1b34d80cefc1.png)
![image](https://user-images.githubusercontent.com/114638578/192943911-31a29630-bb71-4b2e-836c-c10315996c5c.png)


# 项目后台截图
![image](https://user-images.githubusercontent.com/114638578/192943916-e22c87ec-7e27-4d4a-942b-c5a8423240a7.png)
![image](https://user-images.githubusercontent.com/114638578/192943924-0ceeeb01-1a4c-4411-b5a0-cc2301d684dc.png)
![image](https://user-images.githubusercontent.com/114638578/192943931-f034187f-ad52-44de-b81e-e900bd69892f.png)

# 部署教程：
### 0. 了解小程序云开发的基础知识
-  参考微信小程序官方文档：
- https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html
- https://developers.weixin.qq.com/miniprogram/dev/wxcloud/quick-start/miniprogram.html

### 1 源码导入微信开发者工具
![image](https://user-images.githubusercontent.com/114638578/192943947-74e4d3be-a755-4f4d-80b9-34921632b5f3.png)
  

 

### 2 开通云开发环境
 -  参考微信官方文档：https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html
- 在使用云开发能力之前，需要先开通云开发。 
- 在开发者工具的工具栏左侧，点击 “云开发” 按钮即可打开云控制台，根据提示开通云开发，并且创建一个新的云开发环境。
![image](https://user-images.githubusercontent.com/114638578/192943956-e127c5af-d04a-408a-a791-9d17b9d29f1e.png)
- 每个环境相互隔离，拥有唯一的环境 ID(拷贝此ID，后面配置用到)，包含独立的数据库实例、存储空间、云函数配置等资源；
 

#### 3 云函数及配置
- 本项目使用到了一个云函数school_cloud   
 

- 打开cloudfunctions/sport_cloud/comm/ccmini_config.js文件，配置后台管理员账号和密码

![image](https://user-images.githubusercontent.com/114638578/192943971-8c20e51a-a9f9-40c9-b570-b721284b9330.png)

 
#### 4  上传云函数&指定云环境ID

![image](https://user-images.githubusercontent.com/114638578/192943978-1f988acb-5b12-43e1-a98d-f60af0ea4326.png)


#### 5  客户端配置
- 打开miniprogram/app.js文件，配置环境 ID
![image](https://user-images.githubusercontent.com/114638578/192943985-f37c42f5-820e-4ea4-af43-4b55e3f44ef5.png)



#### 6  云函数配置
- 在微信开发者工具-》云开发-》云函数-》对指定的函数添加环境变量 
- [服务端时间时区TZ] =>Asia/Shanghai
- [函数内存] =>128M   
- [函数超时时间] => 20秒
![image](https://user-images.githubusercontent.com/114638578/192943992-87bb9694-1ce3-4c9d-a09a-8a3a615f969c.png)
 

 



### 至此完全部署配置完毕。

### 在线演示：
 
![image](https://user-images.githubusercontent.com/114638578/192944001-26ede8c1-d3d2-4c40-81cb-ad72abd6b596.png)


### 如有疑问，欢迎骚扰联系我鸭： 
### 俺的微信:  cclinux0730

  # 与作者技术交流 
- 开发交流，技术分享，问题答疑，功能建议收集，版本更新通知！！

![image](https://user-images.githubusercontent.com/114638578/192944021-0ae02aca-32c4-4130-9224-5a85e9cb0d1a.png)


