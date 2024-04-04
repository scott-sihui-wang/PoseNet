# PoseNet

## Introduction

In this project, I re-implemented `PoseNet` and modified its implementation to minimize its prediction error for `position` and `orientation`.

Please refer to my [report](Report.pdf) to see full technical details.

The dataset used in this project is hosted on `Colab` at [here](https://drive.google.com/drive/folders/1-0DLn_2T54_mlujLH-9cFnTtGxtJrkwO?usp=sharing).

### Experiments

I experimented with 5 variations of `PoseNet` in order to minimize the prediction errors:

- 1. Standard model [Colab Page](https://colab.research.google.com/drive/1pGvKfvcda0PWGRl3hbzq-LN-TXLqmNhy?usp=sharing);
- 2. Standard model with MSE loss [Colab Page](https://colab.research.google.com/drive/13Vz1IYH0RIlTMdHgSAhcC1pEdpoFcpxe?usp=sharing);
- 3. Modified model [Colab Page](https://colab.research.google.com/drive/1XCdGusWJz8gw-56jyv5UuauiDVIaymsj?usp=sharing);
- 4. Modified model with rescaling of the position values [Colab Page](https://colab.research.google.com/drive/1LA7sY0f3JjhGVty6IVu8DKRb6-cet8G_?usp=sharing);
- 5. Modified Model with Normalization of the Position Values [Colab Page](https://colab.research.google.com/drive/1PHdQss_bWv4tbT1i2bsC4i2T3W0xgMR5?usp=sharing).

So far, the best result is obtained by training _Model 3_ for 500 iterations.

**Topics:** _Computer Vision_, _PoseNet_, _Pose Estimation_

**Skills:** _Pytorch_, _Python_, _Deep Neural Networks_, _Jupyter Lab_, _Colab_
