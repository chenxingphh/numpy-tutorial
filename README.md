# numpy-tutorial

![Alt text](https://github.com/chenxingphh/numpy-tutorial/blob/main/numpy/np_01.png)

    Numpy(Numerical python)是一个用于处理维度数组和矩阵运算的Python三方库。Numpy的运行速度很快，主要包括以下功能：
    1、提供ndarray的N维数组对象
    2、数据切片、广播功能 
    3、随机数生成、线性代数、傅里叶变换等功能

* [numpy_02_数组创建&属性](https://github.com/chenxingphh/numpy-tutorial/blob/main/numpy/numpy_02_%E6%95%B0%E7%BB%84%E5%88%9B%E5%BB%BA%26%E5%B1%9E%E6%80%A7.ipynb)
  - 创建数组
      - 从List,tuple中初始化数组（np.array, np.asarray）
      - 从迭代器中创建数组（np.fromiter）
      - 创建数组函数（np.zeros, np.ones, np.random.uniform）
      - 指定取值范围、等比、等差来创建数组((np.arange, np.linspace, np.logspace ))
  - numpy属性
      -  shape: 数组形状
      -  size: 数组大小，即数组元素个数
      -  dtype: 数组类型 
      -  ndim: 数组维度

* [numpy_03_索引&排序](https://github.com/chenxingphh/numpy-tutorial/blob/main/numpy/numpy_03_%E7%B4%A2%E5%BC%95%26%E6%8E%92%E5%BA%8F.ipynb)
  - 基础索引
      - 正向索引，逆向索引
      - 连续取值、连续间隔取值
  - 高级索引
      - 布尔索引
      - 条件索引
      - 花式索引
  - 排序
      - 数组排序
      - 对象排序（多属性，按指定字段进行排序）

* [numpy_04_广播&数组操作&内置数学函数](https://github.com/chenxingphh/numpy-tutorial/blob/main/numpy/numpy_04_%E5%B9%BF%E6%92%AD%26%E6%95%B0%E7%BB%84%E6%93%8D%E4%BD%9C%26%E5%86%85%E7%BD%AE%E6%95%B0%E5%AD%A6%E5%87%BD%E6%95%B0.ipynb)
  - 广播(Broadcast)
  - 数组操作
    - 修改形状(reshape)
    - 对换维度(np.transpose)
    - 修改维度(np.expand_dims, np.squeeze)
    - 数组拼接(np.concatenate, np.hstack, np.vstack)
  - 常用内置函数
    - 三角函数(np.sin,np.cos,...)
    - 向上和向下取整(np.ceil, np.floor)
    - 舍入函数(np.around)

* [numpy_05_统计函数&线性代数](https://github.com/chenxingphh/numpy-tutorial/blob/main/numpy/numpy_05_%E7%BB%9F%E8%AE%A1%E5%87%BD%E6%95%B0%26%E7%BA%BF%E6%80%A7%E7%BB%9F%E8%AE%A1.ipynb)
  - 统计函数
    - 最值函数(np.amin, np.amax, np.argmin, np.argmax)
    - 均值，方差，标准差
    - 分位数，中位数，极差
  - 线性代数
    - 点积(np.dot)
    - 向量内积(np.inner) 
    - 矩阵乘法(np.matmul)
    - 同位置元素相乘
    - 行列式
    - 逆矩阵（线性方差解）

## License
[MIT LICENSE](LICENSE)
