# cAAE

code for Unsupervised Detection of Lesions in Brain MRI using constrained adversarial auto-encoders, [https://arxiv.org/abs/1806.04972](https://arxiv.org/abs/1806.04972)
AAE model is implemented based on [this github repo](https://github.com/aubreychen9012/Adversarial_Autoencoder)

dataset: [Cambridge Centre for Ageing and Neuroscience (Cam-CAN) dataset](http://www.cam-can.org/index.php?content=dataset) 

Required: python>=2.7, tensorlayer, tensorflow>=1.0, numpy

train model:  python main.py --model_name "cAAE" --z_dim "128"
