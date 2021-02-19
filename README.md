# CourseTable
基于Android的课程表系统<br>
使用SQlite数据库，handler技术、cardview控件等进行实现
参考自https://github.com/cangeBig/2018118117_Android/tree/master/%E6%9C%9F%E6%9C%AB%E5%A4%A7%E4%BD%9C%E4%B8%9A

## 1.系统功能模块划分

![img1](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E5%AD%A6%E7%94%9F%E8%AF%BE%E7%A8%8B%E8%A1%A8%E5%BA%94%E7%94%A8%E5%8A%9F%E8%83%BD%E6%A8%A1%E5%9D%97%E5%9B%BE.png)

课程管理模块包含课程添加、课程修改、课程查看和课程删除四个子模块，他们一起实现了课程表的增、删、改、查。

  关于模块是本系统的基本信息。

## 2.数据库设计

![img2](https://github.com/Declan-Cai/CourseTable/blob/master/images/E-R%E5%9B%BE.png)

![image-20210219172601221](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E6%95%B0%E6%8D%AE%E5%AD%97%E5%85%B8.png)

## 3.流程图

![img3](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E6%B7%BB%E5%8A%A0%E8%AF%BE%E7%A8%8B%E6%B5%81%E7%A8%8B%E5%9B%BE.png)

![img4](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E4%BF%AE%E6%94%B9%E3%80%81%E5%88%A0%E9%99%A4%E3%80%81%E6%9F%A5%E7%9C%8B%E8%AF%BE%E7%A8%8B%E6%B5%81%E7%A8%8B%E5%9B%BE.png)

## 4.运行效果

![img5](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E8%B5%B7%E5%A7%8B%E6%AC%A2%E8%BF%8E%E9%A1%B5.png)
欢迎页面，点开程序显示3s，类似广告页面

![img6](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E8%AF%BE%E7%A8%8B%E8%A1%A8%E4%B8%BB%E9%A1%B5%E9%A1%B5%E9%9D%A2.png)
课程表主页

![img7](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E8%AF%BE%E7%A8%8B%E6%B7%BB%E5%8A%A0activity.png)
添加课程

![img8](https://github.com/Declan-Cai/CourseTable/blob/master/images/%E6%9F%A5%E7%9C%8B%E8%AF%BE%E7%A8%8B%E9%A1%B5%E9%9D%A2.png)
查看课程
