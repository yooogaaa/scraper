## 【Python爬虫】研报提取
### 1. 项目简介
该脚本用于根据关键词和时间提取199IT和贝恩中国网页上的研报，包括研报的发布时间、内容标签、标题和链接。

报告提取逻辑：
- 199IT：当用户输入的任一关键词出现**报告的标签或标题**中时，报告将被提取。
- 贝恩中国：当用户输入的任一关键词出现在**报告的标签、标题或描述**中时，报告将被提取。
### 2. 使用说明
Step 1：打开终端（MacBook）或者命令提示符（Windows），切换到存储reports.py的文件夹路径。

```cd /Users/{your name}/Desktop/reports```

![Step 1（以终端为例）](/Users/xiada/Downloads/python/md/md1.jpg)

Step 2：输入以下代码运行脚本，根据提示输入需要提取的报告关键词和报告发布的起始年份，然后按回车提取研报。

```python3 reports.py```

![Step 2（以终端为例）](/Users/xiada/Downloads/python/md/md2.jpg)

Step 3：当窗口界面出现 *报告已经提取完成！* 时，切换到存储reports.py的文件夹，相应的Excel文件已生成。

![Step 2（以终端为例）](/Users/xiada/Downloads/python/md/md3)
![Step 2（以终端为例）](/Users/xiada/Downloads/python/md/md4)

### 3. 作者
Github：@xd11997

小红书：@lemon_water-

email：xd11997@163.com

作者留言：本人为consulting初入职场打工人，为对抗耗时的research工作在空余时间创建此脚本。
此脚本在持续优化中（例如增加研报数据来源），欢迎大家提出问题/优化意见。希望对您有帮助！

此脚本未经作者允许不可用于商业目的。





