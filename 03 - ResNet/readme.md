# Deep Residual Learning for Image Recognition

## Abstract
Deeper neural networks are more difficult to train. We present a residual learning framework to ease the training of networks that are substantially deeper than those used previously. We explicitly reformulate the layers as learning residual functions with reference to the layer inputs, instead of learning unreferenced functions. We provide comprehensive empirical evidence showing that these residual networks are easier to optimize, and can gain accuracy from considerably increased depth. On the ImageNet dataset we evaluate residual nets with a depth of up to 152 layers—8× deeper than VGG nets but still having lower complexity. An ensemble of these residual nets achieves 3.57% error on the ImageNet test set. This result won the 1st place on the ILSVRC 2015 classification task. We also present analysis on CIFAR-10 with 100 and 1000 layers. The depth of representations is of central importance for many visual recognition tasks. Solely due to our extremely deep representations, we obtain a 28% relative improvement on the COCO object detection dataset. Deep residual nets are foundations of our submissions to ILSVRC & COCO 2015 competitions1 , where we also won the 1st places on the tasks of ImageNet detection, ImageNet localization, COCO detection, and COCO segmentation.
## Research
You Can read the paper from [Here](https://arxiv.org/pdf/1512.03385.pdf)

## Requirements:

This project uses Python 3.9

Create a virtual env with the following command:

```
conda create --name project-setup python=3.9
conda activate project-setup
```

Install the requirements:

```
pip install -r requirements.txt
```

### Training

After installing the requirements, in order to train the model update model configuration to meet your needs and simply run:

```
!python train.py
```

## Monitoring
[wandb link](https://wandb.ai/muhammed266/resnet?workspace=user-muhammed266)

### Training Info
<p align="center">
    <img src="assets/train_info.jpg" width="800"\>
</p>
