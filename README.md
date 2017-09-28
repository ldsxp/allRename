# allRename

这是一个文件批量重命名工具

想法来源于在Windows下对文件批量重命名时的不方便
在业余时间完成这样一个小工具，希望大家用的开心

程序中所引用库均为Python3之后的自带库，不需安装其他依赖，使用Tkinter绘制GUI界面

程序将文件批量重命名的过程分为了四个步骤：
  1. 载入文件：这一步将要重命名的文件全部选中，并可以进行筛选与过滤。
  2. 添加规则：可以自定义的组合程序中现有的规则。
  3. 预览变化：可以将文件名的变化在未更名之前预览（这一步不进行真的更名）。
  3. 确认变化：在确认变化之后文件名将按照预览的样子发生变化。

现有的一些规则：
  1. 移除指定字符：将文件中的指定字符移除
  2. 清空所有字符：将文件名清空
  3. 添加汉字/数字编号：在文件名的末尾添加从1开始的汉字/数字编号
  4. 替换指定字符：将文件名中的指定字符替换为另外的指定字符
  5. 按位置添加：在文件名的指定位置添加指定字符
  6. 按位置删除：删除文件名中指定位置后的指定个数的字符
  7. 大/小写化：将文件名中的字母统一变为大/小写

现有的一些小工具：
  1. 备份与文件名还原：支持对要重命名的文件进行文件名备份，并可以通过备份文件还原文件名。
  2. 规则文件导出与载入：可以自定义规则列表并进行导出和载入。
  3. 文件过滤器：现阶段支持通过文件类型过滤文件。

---

计划将要实现的规则：
  1. 添加文件日期：可以选择文件的创建日期/修改日期添加至文件名
  2. 添加文件哈希值：可以自主选择添加文件的哈希值（现阶段准备支持MD5，SHA1）
  3. 支持正则表达式修改：可以自定义正则对文件名进行修改。
  4. 音乐文件信息支持：对音乐文件提取相关信息组合

计划要实现的功能：
  1. 实现Treeview中的 \<del\> 键删除功能 (2017-09-29 已实现)
  2. 实现规则Treeview中规则拖动变化顺序功能 (2017-09-29 已实现)

计划将要实现的小工具：
  1. 在文件过滤器中添加通配符过滤器
  2. 在文件过滤器中添加正则表达式过滤器

---
*近期刚刚开学事情比较多，所以项目更新暂停一个半月，希望大家理解，谢谢大家的支持！(2017-09-29)

*感谢V2EX上朋友们提出的意见，我会努力把代码写得更好
