# ESRGAN Implementation

This is a PyTorch implementation of the paper [ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks](https://arxiv.org/abs/1809.00219). The code is based on [this](https://www.youtube.com/watch?v=ZM4_s5dAWpI&list=PLhhyoLH6IjfxeoooqP9rhU3HJIAVAJ3Vz&index=32) tutorial by Aladdin Persson.

## Downloading the weights

You can download the weights from [here](https://github.com/aladdinpersson/Machine-Learning-Collection/releases/tag/1.0).

## Testing the model

Create folders named `dataset` and `evaluation` in the root directory. Put the images you want to test in the `dataset` folder. In the train.py file, change the `try_model` variable to `true`. Then run the following command:

```bash
python train.py
```

The output images will be saved in the `evaluation` folder.
