# GAN Dog Net

This dataset was taken from a paper from Khosla, and contains 20,000 images of dogs, with 120 different breeds!  

## 1. Summary 
Here we take a fairly small dataset to train a convolutional neural GAN.  

##### Technical Overview
The pitfall of GANs are that they require massive amounts of compute power to train, meaning they need stacks of GPUs to train. GANs are essentially 2 neural networks, in this case CNNs (convolutional neural networks), competing against each other. Currently the model was trained locally with a fairly weak GPU so only 64 X 64 iamges were created with a simple architecture.

Another repo will be made when the Style2GAN dog model is created.

## 2. Results

- fill

  
## 3. Data Description

20,000 images of dogs
120 breeds
Labels include but not needed for this project

  
## 4. To Do List
- [x] Make a simple GAN architecture and produce suspect looking dogs
- [x] Request free GPU compute power from AWS 
- [ ] Use instance to train using a StyleGAN2 on dataset to produce quality dog photos
- [ ] Tenative on results 


## 5. References

Aditya Khosla, Nityananda Jayadevaprakash, Bangpeng Yao and Li Fei-Fei. Novel dataset for Fine-Grained Image Categorization. First Workshop on Fine-Grained Visual Categorization (FGVC), IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2011.

http://vision.stanford.edu/aditya86/ImageNetDogs/
