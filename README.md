## 一、项目简介

基于Python Flask后端框架和BootStrap4前端开发的学生选课系统设计。本系统分为管理员、老师、学生三个角色。其中要求管理员账号五位（默认admin,123456）、老师账号4位、学生账号8位，密码默认都是123456。

管理员主要功能有学生管理：学生管理（录入学生：先检测学生表中是否存在学号冲突的学生，若无则插入此学生信息。删除学生：先查询出此学生所有已选课程，系统将其全部退选后，再删除此学生。）、教师管理（教师管理功能校验同学生管理一致）、课程管理、选课管理、学院管理、专业管理；注意删除功能会同步删除相关数据库信息，例如删除学院会同步删除学院下的教师、专业等。同理删除专业也会删除相关的信息。

教师功能有：查询教师个人信息（密码修改）、查看学生选课详情、录入学生课程的成绩。

学生功能：查询学生个人信息（密码修改）、专业信息、学院信息、查询已选课程信息，更换已选课程授课教师、退课、查询所有开设课程的信息、查询已选课程的成绩。

## 二、项目技术

Flask后端框架、python、sqlLite数据库、BootStrap前端框架。

## 三、项目功能

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image002.png)

 

## 四、运行截图



 

系统首页：

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image004.png)



学生功能：

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image006.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image008.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image010.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image012.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image014.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image016.png)



教师功能：

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image017.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image019.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image021.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image023.png)



管理员功能：

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image025.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image027.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image029.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image031.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image033.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image035.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image037.png)

![img](https://github.com/UserXiaohu/crouse_manager/blob/main/img/clip_image039.png)