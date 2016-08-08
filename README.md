## Citation

@article{He2015,
    author = {Kaiming He and Xiangyu Zhang and Shaoqing Ren and Jian Sun},
    title = {Deep Residual Learning for Image Recognition},
    journal = {arXiv preprint arXiv:1512.03385},
    year = {2015}
}

##Introduction

Reimplementation ResNet on cifar10

##Structure

The network structure is here:[ethereon](http://ethereon.github.io/netscope/#/gist/544993a5985bb87e11443dc1dbcb4881)

##Usage

for training
```
caffe train -solver=solver.prototxt -gpu 0
```

for testing 
```
caffe test -model=res20_cifar_train_test.prototxt -weights=ResNet_20.caffemodel -gpu 0
```