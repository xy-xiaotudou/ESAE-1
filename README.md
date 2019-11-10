# ESAE: Evolutionary Strategy-based Architecture Evolution

Xue Gu, Ziyao Meng, Yanchun Liang, Dong Xu, Han Huang,Xiaosong Han, and Chunguo Wu

## Requirements

- python =3.6
- keras = 2.2.2
- tensorflow-gpu =1.10.0
- numpy
- pandas

## Methods
![The encoding scheme](https://github.com/xy-xiaotudou/ESAE/blob/master/method/encoding%20scheme.png)


## Run example

Adjust the batch size if out of memory (OOM) occurs. It dependes on your gpu memory size and genotype.

- Search

python main.py --dataset fashionmnist --classes 10 

