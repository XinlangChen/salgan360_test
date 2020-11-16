# salgan_test

---

这是复现SalGAN360论文中的代码，在他原有的git仓库中做了对应的修改，使得在配完环境可以直接运行程序，完成对360°图像的显著性预测。详情可参考[https://github.com/XinlangChen/SalGAN360](https://github.com/XinlangChen/SalGAN360)
## Usage

---

To predict saliency maps, run `salgan360.m` after specifying the path to images and the path to the output saliency maps
## Software frameworks

---

- lasagna  [https://lasagne.readthedocs.io/en/latest/user/installation.html](https://lasagne.readthedocs.io/en/latest/user/installation.html)
```bash
pip install --upgrade https://github.com/Theano/Theano/archive/master.zip
pip install --upgrade https://github.com/Lasagne/Lasagne/archive/master.zip
```

- theano  [http://deeplearning.net/software/theano/install.html](http://deeplearning.net/software/theano/install.html)
```bash
conda install numpy scipy mkl
pip install parameterized
conda install theano pygpu
```

- python 2.7
- ubuntu 18.04
- opencv-python
```bash
pip install opencv-python==3.3.0.10 -i https://pypi.doubanio.com/simple
```


