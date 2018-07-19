# Python environment with requirements.txt

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/binder-examples/requirements/master)

A Binder-compatible repo with a `requirements.txt` file.

Access this Binder at the following URL: 

http://mybinder.org/v2/gh/restry/binder-notebook/python2

## Udacity 机器学习的练习代码, 

使用前先clone, 注意设置目录

` python
  !git clone https://github.com/udacity/ud120-projects
  import os
  os.chdir('ud120-projects/目录')
`

ipynb文件描述

- descition tree.ipynb 决策树练习代码
- anron.ipynb Dataset 数据集章节, 安然事件检测POI(嫌疑人)

## Notes
The `requirements.txt` file should list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```

The base Binder image contains no extra dependencies, so be as
explicit as possible in defining the packages that you need. This includes
specifying explict versions wherever possible.

In this example we include the library `seaborn`, and our notebook uses it
to plot a figure. 
