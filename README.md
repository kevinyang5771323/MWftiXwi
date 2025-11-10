# 前言

随着新冠疫情的蔓延，高校作为人员密集场所，对于疫情的防控工作尤为重要。为了提高校园疫情管理的效率和准确性，我们开发了基于SSM（Spring、SpringMVC、MyBatis）的校园疫情管理系统。本项目旨在为高校提供一个便捷、高效的疫情管理平台，助力校园疫情防控。

# 内容介绍

本系统主要包括以下功能模块：个人信息管理、健康状况上报、疫情数据统计、通知公告管理等。通过这些模块，可以实现对学生、教职工的健康状况进行实时监控，便于学校及时采取措施，防止疫情蔓延。此外，系统还提供了丰富的数据报表，便于管理人员掌握疫情动态。

# 技术介绍

## 语言：Java

## 使用框架：Spring、SpringMVC、MyBatis

## 前端技术：JS、Vue、CSS3

## 开发工具：IDEA/Eclipse

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12、14、16

# 核心代码

以下为系统中的一个示例代码，展示了如何通过MyBatis实现对学生健康状况的查询：

```java
// mapper接口
public interface StudentHealthMapper {
    @Select("SELECT * FROM student_health WHERE student_id = #{studentId}")
    StudentHealth getStudentHealthById(@Param("studentId") int studentId);
}

// 对应的XML映射文件
<select id="getStudentHealthById" parameterType="int" resultType="com.example.entity.StudentHealth">
    SELECT * FROM student_health WHERE student_id = #{studentId}
</select>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/350907/19/2284/176079/68c2caa9F75bf3f17/f206255ed744d74e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/325641/4/18686/121885/68c2ca81F95cd8da1/4c7f2d7c5cc8cf51.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/338840/31/9722/23707/68c2ca81F64e27692/228e73c1abd955fd.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/331384/30/11994/29236/68c2ca82F4faa03e4/087a72d920d3d5da.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/345650/22/2324/65519/68c2ca82F4248b0df/821f858dfcc647cf.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336892/7/9685/26873/68c2ca82F88e60558/54298a10ed3130c3.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350843/19/2075/30904/68c2ca83F0f201e2b/74857dc321cdc288.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323932/13/18917/58799/68c2ca83F58e5e8b5/0e630271538d42dc.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339212/19/9663/36024/68c2ca84F2c94c3be/bfb6287aaad21709.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/345118/23/2245/78618/68c2ca83F0384030c/d95df482c0db2d44.jpg)

