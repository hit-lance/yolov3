fork[此项目](https://github.com/ultralytics/yolov3/)用来完成哈工大模式识别与深度学习实验6，用YOLOv3进行小麦识别。


## Requirements

Python 3.7 or later with all `requirements.txt` dependencies installed, including `torch >= 1.5`. To install run:
```bash
$ pip install -U -r requirements.txt
```


## Tutorial
  [Notebook](https://github.com/hit-lance/yolov3/blob/master/tutorial.ipynb) 中的代码可以复现模型训练的过程，也可以直接通过Colab<a href="https://colab.research.google.com/github/hit-lance/yolov3/blob/master/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open"></a>打开。训练后的参数、测试的结果和tensorboard文件保存在results文件夹下，文件夹中的plot_tb_curve.py用来绘制学习曲线。其他内容详见实验报告。



