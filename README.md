# CIFAR-10-MULTI-WORKERS

Inspired by [multi worker with keras](https://www.tensorflow.org/tutorials/distribute/multi_worker_with_keras
 "go")

[Start in Google Collab]( 
https://colab.research.google.com/drive/1G-PYWI1YHGrziW-8RY-UG941vLxETaNg?usp=sharing)

**How it works?**  
You need to start all boxes one by one;  
If you want to see how it works without starting in Google Collab, just see the "CIFAR-10.ipynb";  
You will work with the CIFAR-10 model and will do it distributed with three workers;  
They start to work when all of them get the "kernel.py";


**Note:**  
Some times it can not work correctly because Google Collab may not allowed three localhost-workers;  
I have not bugs with two localhost-workers but with three it can be.
