# -
简单的线性回归模型预测房价
导入必要的包：代码开始时导入了 NumPy、Pandas 和 Matplotlib 包，这些是用于数据处理和可视化的常用工具。

读取数据集并进行数据清洗：使用 Pandas 读取名为 'housing.csv' 的数据集，并丢弃了含有缺失值的行。

数据可视化：绘制了三个子图，分别显示房价与房屋面积、人均收入以及房龄的关系。

选择自变量和因变量：将数据集中的自变量和因变量分别赋值给变量 X 和 y。

特征缩放：对自变量进行特征缩放，即将其标准化，使得均值为0，标准差为1。

定义代价函数和梯度下降函数：定义了计算代价函数和执行梯度下降的函数。

设置初始参数并运行梯度下降算法：初始化参数 theta，并运行梯度下降算法来更新参数 theta，使得代价函数最小化。

绘制代价函数的变化：绘制了代价函数随迭代次数的变化图。

预测一个新的房价：用户输入一个新房屋的面积、人均收入和房龄，模型使用训练得到的参数进行预测，并输出预测的房价。
