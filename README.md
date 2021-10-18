# ColorMapGAN-PyTorch
A pytorch implement of ColorMapGAN (TGRS2020)
<a href="https://arxiv.org/pdf/1907.12859.pdf">ColorMapGAN: Unsupervised Domain Adaptation for Semantic Segmentation Using Color Mapping Generative Adversarial Networks</a>

这是对ColorMapGAN的核心方法的实现，总共包含三个文件：

+ deeplabv2.py：这是分割模型，原论文中使用的是Unet，这里我使用的是deeplabv2
+ generator.py：这是ColorMapGAN中的生成器的实现，也是该论文的核心创新点所在
+ discriminator.py：这是ColorMapGAN中的判别器的实现。

这里没有放完整的数据加载、训练、测试的代码，如有需要完整的代码，请关注公众号后在后台留言（微信搜索：阿柴和她的CV学习日记）
[![二维码](https://github.com/AI-Chen/ColorMapGAN/blob/main/qrcode_for_gh_e41e549f33cd_344.jpg "二维码")]
