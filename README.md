<p>
<a href="https://www.amazon.co.jp/dp/4873119065/ref=cm_sw_r_tw_dp_U_x_KiA1Eb39SW14Q"><img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/deep-learning-from-scratch-3.png" height="250"></a>
</p>

## 本书概述

在本书中，我们将创建一个名为“DeZero”的深度学习框架。 DeZero是本书的原创框架。 用最少的代码实现框架的现代功能。 在本书中，我们将通过 60 个步骤完成这个小而强大的框架。 这将加深对 PyTorch、TensorFlow 和 Chainer 等现代框架的了解。

<p>
<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/dezero_logo.png" width="400px" </p>


<p>
  <a href="https://pypi.python.org/pypi/dezero"><img
		alt="pypi"
		src="https://img.shields.io/pypi/v/dezero.svg"></a>
  <a href="https://github.com/oreilly-japan/deep-learning-from-scratch-3/blob/master/LICENSE.md"><img
		alt="MIT License"
		src="http://img.shields.io/badge/license-MIT-blue.svg"></a>
  <a href="https://travis-ci.org/oreilly-japan/deep-learning-from-scratch-3"><img
		alt="Build Status"
		src="https://travis-ci.org/oreilly-japan/deep-learning-from-scratch-3.svg?branch=master"></a>
</p>


## 文件组织

|文件夹名称 |説明         |
|:--        |:--                  |
|[dezero](/dezero)       |DeZero源代码|
|[examples](/examples)     |DeZero的使用实现示例|
|[steps](/steps)|每个步骤文件（step01.py ~ step60.py）|
|[tests](/tests)|DeZero单元测试|


## 所需的外部库

本书使用的Python版本和外部库如下。

- [Python 3系](https://docs.python.org/3/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

它还提供在 NVIDIA GPU 上运行的选项。 在这种情况下，需要以下库。

- [CuPy](https://cupy.chainer.org/) （选项）


## 运行方法

本书讲解的Python文件主要位于[steps](/steps)文件夹中。
要运行它，请运行下面的 Python 命令（您可以从任何目录运行它）。

```
$ python steps/step01.py
$ python steps/step02.py

$ cd steps
$ python step31.py
```

## 演示

DeZero的其它实现示例可以在 [examples](/examples)中找到。

[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/example_tanh.png" height="175"/>](https://github.com/oreilly-japan/deep-learning-from-scratch-3/tree/tanh)[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/example_spiral.png" height="175"/>](/examples/spiral.py)[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/example_gpu.png" height="175"/>](https://colab.research.google.com/github/oreilly-japan/deep-learning-from-scratch-3/blob/master/examples/mnist_colab_gpu.ipynb)

[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/gan.gif" height="175"/>](/examples/gan.py)[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/vae.png" height="175"/>](/examples/vae.py)[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/grad_cam.png" height="175"/>](/examples/grad_cam.py)

[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/style_transfer.png" height="175"/>](/examples/style_transfer.py)[<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-3/images/pythonista.png" height="175"/>](https://github.com/oreilly-japan/deep-learning-from-scratch-3/wiki/DeZero%E3%82%92iPhone%E3%81%A7%E5%8B%95%E3%81%8B%E3%81%99)

