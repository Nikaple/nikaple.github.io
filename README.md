# Chemical Supporting Information Helper

[在线预览](https://nikaple.github.io/dist/index.html)

## 基本使用

### Word设置

#### 设置默认粘贴方式

在Word中选择文件→选项→高级，从其他程序粘贴设置为“合并格式”，即可以默认合并格式粘贴到Word中，省去手动更改格式的步骤。

### <sup>1</sup>H NMR 数据处理

#### 原始数据处理

在谱图软件MestReNova中处理好谱图后，选中氢谱，在菜单栏中单击Multiplets Analysis显示耦合常数，再在其下拉菜单中选择Copy。随后切换到浏览器界面，将刚刚所复制的数据粘贴在<sup>1</sup>H NMR 数据处理的文本框中。无需任何复制操作，即可格式化的数据保存到剪贴板。之后在Word中粘贴即可。

#### 数据检测

将包含氢谱的已处理数据直接粘贴至<sup>1</sup>H NMR 数据处理的文本框后，根据输出框高亮部分寻找错误来源。
 + 无高亮：检测通过！
 + 黄色高亮：此部分数据已被修改；
 + 红色高亮：此信息可能有误；
 + 仅显示错误信息：
   + 谱图数据格式不正确：请检查数据是否以<sup>1</sup>H(<sup>13</sup>C) NMR开头，并以英文句号或英文分号结尾(.或;)；
   + 频率或溶剂信息有误：请检查频率与溶剂信息
