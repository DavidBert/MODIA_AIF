---
modified: 2024-04-04T08:39:56.466Z
title: XAI project
---

# XAI project

## Objective
This is the last part of the project and is totally independent of the previous parts.  
Here you will implement the [Rise method](https://arxiv.org/pdf/1806.07421.pdf) to explain the predictions of a model.  
Start by reading the paper and understanding the method.  
Then implement the method and test it on two models of your choice. To avoid long training times, you will work on [Imagenette](https://s3.amazonaws.com/fast-ai-imageclas/imagenette2.tgz) a subset of ImageNet with 10 classes that we used during the practical sessions.
You will also have to implement the two evaluation metrics, __deletion__ and __insertion__ presented in the [Rise paper](https://arxiv.org/pdf/1806.07421.pdf) to evaluate the explanations produced by the method. 
Once this is done, you will have to evaluate the explanations produced by the [Rise method](https://arxiv.org/pdf/1806.07421.pdf) and compare them with explanations produced by other methods like [LIME](https://arxiv.org/pdf/1602.04938.pdf) or [GradCAM](https://arxiv.org/pdf/1610.02391.pdf).  
Display the explanations produced by the two methods for the two models you chose and evaluate them using the two metrics you implemented.

## Deliverable
- A notebook with the implementation of the Rise method and the evaluation metrics.  
All the code should be well documented and easy to read with clear explanations of the different steps.
- The explanations produced by the method for the two models you chose.
- The evaluation of the explanations using the two metrics.

