# NST_2pics
Pytorch Neural Style Transfer (**NST**) algorithm based on pretrained VGG19 CNN. Style is transfered from two distinct pictures, one of which is local style parent and the other is global style parent. As result one have image with local style patterns from image_1 and global abstract style features from image_2 with saved content from initial pic.
Code is based on [pytorch tutorial](https://pytorch.org/tutorials/advanced/neural_style_tutorial.html) and [article](https://arxiv.org/abs/1508.06576).<br/>
<br/>
Below are two examples of style transfer algorithm applied to cat picture as contest and two different pair of style images.
|Example 1|Example 2|
|---|---|
|![](https://github.com/addward/NST_2pics/blob/master/images/cat_stylized_1.png)|![](https://github.com/addward/NST_2pics/blob/master/images/cat_stylized_2.png)|
