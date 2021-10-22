# GAN Dog Net
This dataset was taken from a paper from Khosla, and contains 20,000 images of dogs.


## 1. Summary 
GANs are fairly new deep learning architectures and have many use cases. These applications:
- create synthetic data for ML algorithms
- generate new images, art or even mimic styles
- create images of dogs

Here we train a simple CNGAN from scratch, meaning this will probably produce very **poor images of dogs**. However, this is more of an exercise to see how GANs learn in an unsupervised fashion. 

##### Technical Overview
The pitfall of GANs are that they require massive amounts of compute power to train, meaning they need stacks of GPUs to train. GANs are essentially 2 neural networks, in this case CNNs (convolutional neural networks), competing against each other. The models were trained locally with a fairly weak GPU (NVIDA GTX 1050 Ti) so only 64 X 64 images were created with a simple architecture.

Another repo will be made when the Style2GAN dog model is created.

## 2. Results
I did not perform any data augmentations because creating a good CNGANs model would be impossible with this setup (weak GPU and small dataset). Regardless, this was an interesting, informative exercise. I trained the models for approximately ~75 epochs. It starts off as a random blobs and slowly turns into grouped blobs with some structure. By the 75th epoch the model starts producing producing shapes of a dog. With more training the images would start form shapes of dogs but probably would not detailed, because of the low resolution. 

[Click here to view generated imgs]https://github.com/victorvvu/Simple_CNGAN_Dogs/tree/main/Generator_Results

1st training epoch

![40th](https://github.com/victorvvu/Simple_CNGAN_Dogs/blob/main/Generator_Results/generated_img0_100_.png?raw=true)


Half way through training

![40th](https://github.com/victorvvu/Simple_CNGAN_Dogs/blob/main/Generator_Results/generated_img40_600_.png?raw=true)

Last training epoch

![Last EPOCH](https://github.com/victorvvu/Simple_CNGAN_Dogs/blob/main/Generator_Results/generated_img76_0_.png?raw=true)


Here is a GIF (of the generator training)

![DCGAN](https://github.com/victorvvu/Simple_CNGAN_Dogs/blob/main/Generator_Results/dcgan.gif?raw=true)

  
## 3. Data Description
Sample from dataset



![Sample2](https://github.com/victorvvu/Simple_CNGAN_Dogs/blob/main/dog_imgs/n02100236_2204.jpg?raw=true)


- 20,000 images of dogs
- 120 breeds
- labels include but not needed for this project

  
## 4. To Do List
- [x] Make a simple GAN architecture and produce suspect looking dogs
- [ ] Train using a StyleGAN2 on dataset to produce quality dog photos
- [ ] Tenative on results 


## 5. References

Aditya Khosla, Nityananda Jayadevaprakash, Bangpeng Yao and Li Fei-Fei. Novel dataset for Fine-Grained Image Categorization. First Workshop on Fine-Grained Visual Categorization (FGVC), IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2011.

http://vision.stanford.edu/aditya86/ImageNetDogs/
