# HADepth

This is the official PyTorch implementation of the method  as described in

"HADepth: Highlight-aware monocular depth estimation for endoscopy" submitted to **Signal, Image and Video Processing**.

**We are organizing the code and expect to complete it within a few weeks.**



## ⚙️ Setup

Our experimental configuration and hyperparameters are as follows:

| Parameter             | Configuration           |
| --------------------- | ----------------------- |
| CPU                   | Intel Core i9-10980XE   |
| GPU                   | NVIDIA GeForce RTX 3090 |
| Operating system      | Ubuntu 20.04.5 LTS      |
| CUDA                  | 11.7                    |
| Python version        | 3.9.17                  |
| PyTorch version       | 1.13.0                  |
| Batch size            | 8                       |
| Epochs                | 20                      |
| Initial learning rate | 0.0001                  |
| Optimizer             | Adam                    |





## 💾 Datasets

The datasets are publicly available at the following URLs:  

**SCARED**: https://endovissub2019-scared.grand-challenge.org/

**ColonDepth**: http://cmic.cs.ucl.ac.uk/ColonoscopyDepth/

For more details of the the SCARED, please follows the instructions in [AF-SfMLearner](https://github.com/ShuweiShao/AF-SfMLearner).


## 📊 Evaluation



## 📦 Pretrained Models

We have released our pretrained models in this link: [google drive]()





## Acknowledgement

We thank the authors of [AF-SfMLearner](https://github.com/ShuweiShao/AF-SfMLearner), [IID-SfMLearner](https://github.com/bobo909/IID-SfmLearner), [Depth Anything](https://github.com/LiheYoung/Depth-Anything) and [EndoDAC](https://github.com/BeileiCui/EndoDAC) for opening source their code.
