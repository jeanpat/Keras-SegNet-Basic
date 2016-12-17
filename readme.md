### SegNet-Basic:
---

What is Segnet?

* Deep Convolutional Encoder-Decoder Architecture for Semantic Pixel-wise Image Segmentation

 **Segnet** = **(Encoder + Decoder)** +  **Pixel-Wise Classification** layer

##### *[SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation (Vijay Badrinarayanan, Alex Kendall, Roberto Cipolla, Senior Member, IEEE) arXiv:1511.00561v3](https://arxiv.org/abs/1511.00561)*


What is SegNet-Basic?

* *"In order to analyse SegNet and compare its performance with FCN  (decoder  variants)  we  use  a  smaller  version  of  SegNet, termed SegNet-Basic ,  which  ha  4  encoders  and  4  decoders. All the encoders in SegNet-Basic perform max-pooling and subsampling and the corresponding decoders upsample its input using the  received  max-pooling  indices."*

Basically it's a mini-segnet to experiment / test the architecure with convnets, such as FCN.


 -----


### Dataset:
---

1. The data required to run the Road Scene Segmentation can be found here in the project as a stored numpy Array. 

2. In case you need the original set, refer to:

	* In a different directory run this to download the [dataset from original Implementation](https://github.com/alexgkendall/SegNet-Tutorial).
	* `git clone git@github.com:alexgkendall/SegNet-Tutorial.git`
	* change `DataPath` to the above directory



----


### To Do:
----

	[ ] SegNet-Basic
	[ ] SegNet
	[ ] Test Accuracy





