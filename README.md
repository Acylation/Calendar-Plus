# Semester Schedule
Generate your personal schedule, which is more flexible

### Features
- Import, find and generate
- Add temp events
- Add repeat events
- Tabs/tags: courses/experiment/meetings/homework/enjoyment etc.
- Sorting rules: by tags, by emergant, by focus, 开小差事件
- Drag & Put into schedule
- Reminder / System Message
- More info when float/longpress

### 新设计
给定时间的日程直接排进日程表，未给定时间的日程作为卡片，先排出时间段，再通过拖动叠放（自动吸附，tag切换、悬浮切换）；时长卡片自行伸缩，半小时为单位；支持左右伸缩和复制，设计手机端交互；日常重复，不定时重复项目

**针对特定学校的课程表导入插件/SchoolImport**  
特殊需求：地点，单双周（要做Calendar）  
父类：日历（节假日安排导入、万年历）  
    年视图，月视图，周视图，日视图  
子类：校历（周次，考试周，报道日，放假日）  
子类：日程表（）写继承  

父类：项目，成员有事件  
子类：课程（课堂，作业，考试），大作业，兴趣爱好，科研课题，学生工作，社团活动etc.

### 策划案
- 模块：
- 需求分析：
- 概要设计：
- 详细设计：
- 编码：
- 测试：
- 发布：

### 项目概述
多功能课表，让学习更放松

- 项目定位：开源化、个性化（特定学校）学习辅助软件；利用常用办公软件Excel，灵活解决实际问题
- 核心功能：输入课程列表；列表转化为课程表；上课提醒
- 核心实现：利用OCR+ Excel 实现课程导入；使用Excel进行课程列表到时间安排的引用；借助VBA实现一些特殊功能，如弹窗提醒等

- 参考：
    - Excel模板
    - iStudiez Pro
    - 超级课程表
- 备注：演讲过程展示Excel模板小样和iStudiez Pro示例；进行需求调查，超级课程表体验
- 注意：自动导入不要绑定，一次性，后期支持手动调整与归零
- 初步设计：
    - 针对学校完成时间段自定义
    - 课程的时间录入节次自动转化为时间，周次控制提醒，录入开学到考试
    - 手动维护，校历
- 分工：
    - 前端
    - 课程列表导入
    - 课程表引用
- 设计：视图（周视图、月视图）
- 学术：通过已有材料和互联网搜索，掌握自己负责部分的
    - Excel引用学习
    - VBA 弹窗
    - UI绘制美工
- 附加
    - Excel 地图
    - 临时事件、周期事件、作业
    - 自习课室推送研究（数据、算法、可视化）
    - GPA计算小工具（问一下BYJ北大的学习助手）
    - 老师信息管理（自定义More Information解决）
- 需求分析：
    - 基本：输入课程列表，导出课程表，上课时间提醒
    - 附加：上课地点提醒，作业管理，老师信息管理，准备资料管理，自习助手，GPA计算器，课室课表；
    - 特殊功能：单双周

### 复盘
第一学期计算机大作业复盘  
基于VBA的课程表  
日程控制：写教程可以慢慢来，不要一口吃成大胖子  
改进：使用难度更高的技术栈，了解基于C++的UI开发；学习HTML技术作为前端，Python+ MySQL作为后端  
技术选项：Python/C++/JavaScript  
前端选项：PyQt，Qt，electron  
移动部署：  

### Reference
[FullCalendar](https://github.com/fullcalendar/fullcalendar): Drag & Drop 卡片式Calendar
