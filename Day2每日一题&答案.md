# 每日一题&答案 - Day2

1. 什么我们从Python开始学习数据分析?
     ● Python 的语法简单，代码可读性高，容易入门，有利于初学者学习。
     ● Python 在数据分析和交互、探索性计算以及数据可视化等方面都有非常成熟的库
     和工具，也有对应的非常活跃的社区。尤其是 Python 中的 Pandas 库在处理中型
     数据方面可以说有着无与伦比的优势，正在成为各行业数据处理任务的首选库。
     ● Python 拥有强大的通用编程能力。Python 不仅在数据分析方面能力强大，在爬
     虫、web、自动化运维甚至游戏等等很多领域都有广泛的应用。这就使公司使用一
     种技术完成全部服务成为可能，有利于各个技术组之间的业务融合。
     ● Python 是人工智能时代的通用语言。

2. 数据分析过程包含哪些步骤？

     提问、整理数据、执行EDA、得出结论（甚至作出预测）、传达结果

3. 什么是探索性数据分析？
  探索性 数据分析 (Exploratory Data Analysis，以下简称 EDA )，是指对已有的数据(特别是
  调查或观察得来的原始数据)在尽量少的先验假定下进行探索，通过作图、制表、方程拟
  合、计算特征量等手段探索数据的结构和规律的一种 数据分析 方法。

4. 常用的可视化图表有哪些类型？至少列举出5种。
  条形图，折线图，组合图，雷达图，散点图，网格图，饼图，漏斗图，热图，风玫瑰图，
  方块图和表盘图以及透视表和垂直表等。

5. 常用的数据分析 Python 库有哪些？至少列举3 个。
  NumPy, Pandas, SciPy, Matplotlib, Seaborn等。

6. Pandas是一个什么工具包？
  Pandas 是 Python 的第三方库，可以快速处理数据集，建立 DataFrame
  · 基于 Numpy 建立的开源库
  · 可快速进行数据分析，数据清理等一系列数据准备工作
  · 有自带的数据可视化特征

7. 什么是 jupyter notebook?
  Jupyter Notebook是基于网页的用于交互计算的应用程序。其可被应用于全过程计算：开
  发、文档编写、运行代码和展示结果。—— Jupyter Notebook官方介绍
  简而言之，Jupyter Notebook是以网页的形式打开，可以在网页页面中直接编写代码和运
  行代码，代码的运行结果也会直接在代码块下显示的程序。如在编程过程中需要编写说明
  文档，可在同一个页面中直接编写，便于作及时的说明和解释。

8. 我们在做项目中会用到 jupyter notebook，里面的文本框使用的 markdown 语法。
  markdown是什么？
  Markdown是格式化语法，可让你加入链接、将文本样式设为粗体或斜体和设置代码格
  式。

9. Jupyter notebook 的文件格式是什么？
  Jupyter notebook 文档可以保存为后缀名为.ipynb的JSON格式文件，不仅便于版本控制，
  也方便与他人共享。

10. Jupyter notebook 文档还可以导出为哪些通用的文件格式？请列举至少两种。

    HTML、LaTeX、PDF等格式。

11. Python 的 import 语句是实现什么功能？
    用于动态加载类和函数

12. %matplotlib inline 这个语句实现什么功能？
    使matplotlib绘制的图形在jupyter notebook直接显示，而不是弹出一个窗口。

13. Csv 文件是什么类型的文件？有什么特点？
    逗号分隔值（Comma-Separated Values，CSV，有时也称为字符分隔值，因为分隔字符
    也可以不是逗号），其文件以纯文本形式存储表格数据（数字和文本）

14. csv 文件和 tsv 文件的区别?
    csv 文件使用逗号分隔数据的文件，tsv 使用 tab 分隔数据的文件。

15. 你 了解的用于数据分析的工具有哪些？请至少列举三个。
    Excel，R，Python，SPSS，SAS，Tableau，PowerBI, MySQL 等。

16. 在python中，报错`IndentationError`一般是因为什么呢？我们应该怎么注意避免出现此类错误？

    一般都是因为缩进问题，python最具特色的就是使用**缩进**来表示代码块， 同一个代码块的语句必须包含相同的缩进空格数，缩进的空格数是可变的，但是有个不成文的规定就是使用**4个空格**的缩进。

    比如：

    ```python
    if True:
        print ("True")
    else:
        print ("False")
    ```

    但如果像如下这样就会因为缩进问题报错：

    ```python
    if True:
        print ("True")
    else:
      print ("False")    # 缩进不一致，会导致运行错误
    ```

17. python中的列表是什么？元组又是什么？他们有什么异同？

    列表和元组都是可迭代类型，他们都包含用逗号隔开的元素，不同的是，列表可以更改，元组不可更改。