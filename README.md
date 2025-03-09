# AWS_SSA_Certification
A preparation process for AWS Solution Architect Associate
# day one
第一阶段：知识输入（9:00-10:30）​
目标：完成S3基础部分学习（对应Stephane课程存储服务模块）​

​9:00-9:45｜核心概念学习

观看Udemy课程 ​S3基础章节​（约1.5倍速，暂停记录关键点）
​重点掌握：
✓ S3的存储桶（Bucket）与对象（Object）核心概念
✓ 存储类型对比：Standard vs IA vs Glacier（记录价格、访问速度、适用场景）
✓ 跨区域复制（Cross-Region Replication）触发条件
​学习方法：
用康奈尔笔记法分三栏记录（主栏知识点/副栏关键词/底栏联想考点）
每学完一个小节（如存储类型），暂停并用费曼技巧向自己复述
​9:45-10:00｜主动休息

闭眼回顾知识点（激活海马体记忆加工）
活动身体+补充水分（避免久坐疲劳）
​10:00-10:30｜知识结构化

用XMind绘制 ​S3知识图谱，包含：
✓ 存储类型对比表（标注考试常见干扰项，如Glacier的3-5小时取回时间）
✓ 生命周期策略（Lifecycle Policy）流程图
✓ 与EC2/EBS的关联场景（如静态网站托管需开启Bucket权限）
​第二阶段：实战强化（10:30-12:00）​
目标：通过习题巩固S3知识并建立考试思维

​10:30-11:15｜专项练习

使用 ​Tutorials Dojo S3专项题库​（优先做20题）
​答题技巧：
题干关键词圈画（如“cost-effective”指向IA/Glacier）
排除法优先排除绝对性描述（如“must”“always”）
​错题处理：
将错题截图粘贴至Notion错题本，标注错误原因（如混淆S3一致性模型）
​11:15-11:30｜深度解析

对照Tutorials Dojo答案解析补全知识漏洞：
✓ 预签名URL（Pre-signed URL）的权限时效性
✓ S3版本控制（Versioning）与MFA删除的关系
回看课程对应片段（2倍速查漏）
​11:30-12:00｜知识迁移训练

打开AWS管理控制台，实操：
✓ 创建S3存储桶并上传测试文件
✓ 配置生命周期策略（体验从Standard到Glacier的转换）
✓ 生成预签名URL测试访问权限
​目标：将理论转化为肌肉记忆，强化“动手即记忆”效果
