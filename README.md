# GAN Dog Net
This dataset was taken from a paper from Khosla, and contains 20,000 images of dogs, with 120 different breeds!  


## 1. Summary 
GANs are fairly new deep learning architectures and have many uses. They have many applications such as:
- create synthetic data for ML algorithms
- generate new images, art or even mimic styles
- create images of dogs

##### Technical Overview
The pitfall of GANs are that they require massive amounts of compute power to train, meaning they need stacks of GPUs to train. GANs are essentially 2 neural networks, in this case CNNs (convolutional neural networks), competing against each other. The model was trained locally with a fairly weak GPU (NVIDA GTX 1050 Ti) so only 64 X 64 iamges were created with a simple architecture.

Another repo will be made when the Style2GAN dog model is created.

## 2. Results

- fill

  
## 3. Data Description
Sample from dataset
![Sample2](https://github.com/victorvvu/Simple_CNGAN_Dogs/blob/main/dog_imgs/n02100236_2204.jpg?raw=true)


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
