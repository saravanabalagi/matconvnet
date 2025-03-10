# MatConvNet: CNNs for MATLAB

Forked from [vlfeat/matconvnet](https://github.com/vlfeat/matconvnet).
Updated vl_compilenn.m and successfully compiled with CUDA 11.1 and MATLAB R2021b. Dockerfile available [here](https://github.com/saravanabalagi/matlab-dockerfile).

```sh
git clone https://github.com/saravanabalagi/matconvnet.git
cd matconvnet

# in matlab shell
addpath matlab
vl_compilenn('enableGpu', true)
```

**MatConvNet** is a MATLAB toolbox implementing *Convolutional Neural
Networks* (CNNs) for computer vision applications. It is simple,
efficient, and can run and learn state-of-the-art CNNs. Several
example CNNs are included to classify and encode images. Please visit
the [homepage](http://www.vlfeat.org/matconvnet) to know more.

In case of compilation issues, please read first the
[Installation](http://www.vlfeat.org/matconvnet/install/) and
[FAQ](http://www.vlfeat.org/matconvnet/faq/) section before creating an GitHub
issue. For general inquiries regarding network design and training
related questions, please use the
[Discussion forum](https://groups.google.com/d/forum/matconvnet).
