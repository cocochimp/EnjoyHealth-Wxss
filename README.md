# EnjoyHealth健康小程序

💖基于weui-wxss框架开发的的轻享健康微信小程序平台，旨在解决健康外卖餐饮问题

github地址：https://github.com/cocochimp/EnjoyHealth-Wxss



# 📚页面展示📚

## 登录界面

进入微信小程序，填写手机号码和密码之后便可进行小程序主界面，登录界面：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090450.jpg)

## 主页

本轻享健康小程序界面如下图所示，主要分为4个管理模块，下面将按照模块来说明小程序的操作流程与方法，主页界面：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090542.jpg)



 

### 转盘

该模块主要实现配餐的随机选择，用户可通过一键点击，由系统随机选择配餐方案，主要按钮为中心“GO”按钮，点击即可推荐配餐：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090559.jpg)



操作过程：点击中心的“GO”按钮，等待界面动画结束后在下方可查看结果：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090611.jpg)

 

### 热量

该模块主要实现通过用户输入的个人信息，计算并显示其每天可摄入的热量：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090632.jpg)



操作过程：通过点击选择性别类型，输入身高、体重、年龄信息，点击“计算”按钮，即可计算并显示用户每天可摄入的热量值：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090644.jpg)



 

### 菜谱

该模块主要实现展示各项菜品的烹饪步骤和原料，用户可根据自身需求选择不同的菜谱类别，主要有“时段菜谱”、“懒人菜谱”、“健身菜谱”，将不同菜品进行归类，供用户进行选择查看：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090705.jpg)

操作过程：用户点击左侧栏中某一菜谱类别，接着选择点击右侧栏目中显示的菜品，即可展示所选择的菜品烹饪步骤和原料：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090713.jpg)



 

### 推荐

该模块主要实现根据用户选择的口味偏好向用户推荐饮食套餐：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090739.jpg)

操作过程：用户通过点击选择喜欢的菜系和不喜欢的菜系，点击下一步，点击“开始定制套餐！”按钮，即可显示推荐的饮食套餐：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090745.jpg)

 

## 菜品识别

该模块主要实现了对菜品类别的实时检测，检测用户可通过点击上传食物照片，一次只能上传并识别一张图片，页面中的两个按钮分别是“上传食物”和“识别菜品”：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090808.jpg)

操作过程：用户点击“上传食物”按钮，上传待识别的菜品图片，点击“识别菜品”按钮对菜品进行识别，即可在下方的菜品详情中查看该菜品的名称和热量值：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090814.jpg)



## 订餐

该模块主要功能是提供各类食物商品供用户选择购买，左侧栏的各个按钮是将各类食物进行分类，点击即可显示该类别的食物，右侧栏可点击选择食物进行添加购买：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090833.jpg)

操作过程，用户先点击左侧所需食物的类别，接着点击右侧对应食物的“添加”按钮，即可进行结算：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090838.jpg)

 

## 我的

该模块主要是方便用户管理信息，主要有4个功能，分别是：待支付、代发货、待收货、已完成和营养师服务：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090906.jpg)

营养师服务模块主要是实现用户对营养信息的咨询功能：

![img](https://cocochimp-img.oss-cn-beijing.aliyuncs.com/23-03/20230420090912.jpg)