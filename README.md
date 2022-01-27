# Machine Vision project

This project was performed for machine vision class at University Paris Sacaclay - M1 E3A

* Introduction

The aim of this work is to have better understanding in Machine learning/Deep learning concepts which are frequently used in computer vision fields. The project is composed of 2 parts. Convolutional Neural Network(CNN) is a multilayered neural network with a special architecture which allows to detect features of data. It has been used in many computer vision application such as image recognition, segmentation, style transfer and classification. In this paper, we are going to build a VGG-16 based CNN for classifying images, to classify cow and horse with limited numbers of datasets. It is hard to get enough data for sufficient machine training in real life. By doing data augmentation implementing DCGANs, we show that we could improve classification accuracy. 

In second part of the work, we show image to image translation for example cow to horse and vise versa. There have been many studies on neural style transfer. At the same time, Image to Image translation studies have been progressed from paired images into unpaired images. It is because obtaining paired data for training is expensive and difficult compared to unpaired images. CycleGANs is a technique for training unsupervised image translation models via the GANs architecture using unpaired collections of images from two different domains. 

In a summary, This project consist of 3 parts : 
- Building a classifier using VGG 16 with Cow and Horse dataset
- Data augmentation using GANS
- Styletransfer between Horse and Cow


\begin{thebibliography}{1}


%%%%~\cite{cnn}
\bibitem{alexnet}
A. Krizhevsky, I. Sutskever, and G. Hinton, “ImageNet Classification
with Deep Convolutional Neural Networks,” Advances in neural
information processing systems, vol. 25, no. 2, 2012.
\bibitem{cnn}
K. Simonyan, and A. Zisserman, “Very Deep Convolutional Networks
for Large-Scale Image Recognition,” Computer Science, 2014.
\bibitem{vgg}
https://neurohive.io/en/popular-networks/vgg16/
\bibitem{GAN} 
I. Goodfellow, J. Pouget-Abadie, M. Mirza, B. Xu, D.Warde-Farley, S. Ozair, A. Courville, and Y. Bengio, “Generative adversarial nets,” in Advances in Neural Information Processing Systems, 2014
\bibitem{DCGAN}
A. Radford, L. Metz, and S. Chintala, “Unsupervised representation learning with deep convolutional generative adversarial networks,” in ICLR, 2016
\bibitem{pix2pix}
P. Isola, J.-Y. Zhu, T. Zhou, and A. A. Efros. Image-toimage
translation with conditional adversarial networks. In CVPR, 2017
\bibitem{cycleGAN}
J.-Y. Zhu, T. Park, P. Isola, and A. A. Efros, “Unpaired image-to-image translation using cycle-consistent adversarial networks,”
in Proceedings of the IEEE Conference on Computer Vision and Pattern
Recognition, 2017
\bibitem{patchGAN}
P. Isola, J.-Y. Zhu, T. Zhou, and A. A. Efros. Image-toimage
translation with conditional adversarial networks. In CVPR, 2017
\bibitem{generator_cycle}
https://towardsdatascience.com/a-gentle-introduction-to-cycle-consistent-adversarial-networks-6731c8424a87
\bibitem{resnet}
K. He, X. Zhang, S. Ren, and J. Sun, "Deep residual learning for image
recognition.", 2015
\end{thebibliography}
