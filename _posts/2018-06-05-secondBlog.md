---
layout: post
title:  "Welcome to MUSANL!"
date:   2018-06-05 16:50:13 +0800
categories: Default
tags: blog
comments: 1
---
## 测试博客

  - [我的github主页](https://github.com/MUSANL)
  
  
  ![](/assets/res/user.png)
  
> 我的博客
```java
public class student{}
  create table Student
(
	studentId int primary key auto_increment not null,														-- 学生编号
	studentName varchar(20),                                                      -- 学生姓名
	studentSex varchar(10),																												-- 学生性别
	studentIdCard varchar(20),																										-- 学生身份证号
	studentPhone varchar(20),																											-- 学生手机号
	studentPwd varchar(20),																												-- 学生密码
	classesId int,								      																					-- 学生班级
	studentNo varchar(20),							      																		-- 学生学号
	studentInDate date,																														-- 入学时间 --毕业时间与班级一致
	upuid int,								      																							-- 操作人员
	uptime timestamp							      																					-- 更新时间
)
```
