# Potrait-Segmentation-BodyPix

## BodyPix

BodyPix is an open-source machine learning model which allows for person and body-part segmentation with TensorFlow. With default settings, it estimates and renders person and body-part segmentation at 25 fps on a 2018 15-inch MacBook Pro, and 21 fps on an iPhone X.

![](https://i.gzn.jp/img/2019/11/19/bodypix-2-real-time-person-segmentation/s0267.jpg)

## Background Blur (Bokeh Effect)

This body part segmentation can be used for foreground-background seperation in potrait photos, and a bokeh effect can be applied using the resulting mask from the model.

* ### Original Image

![](sample/0x0.jpg)

* ### Bokeh Applied

![](sample/bokeh_blur.jpg)

## Virtual Background

Similarly, the resulting mask can also be used for replacing the background with a virtual background, which are increasingly becoming popular in online conference calls.

* ### Virtual Background Applied

![](sample/virtual_bg.jpg)
