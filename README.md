# MSP-CD

The pytorch implementation for "Multi-Stage Progressive Change Detection on High-resolution Remote Sensing Imagery". 


## Requirements

- Python 3.7
- Pytorch 1.10.0


## Datasets

- Download the [Levir-CD Dataset](https://justchenhao.github.io/LEVIR/)
- Download the [Lebediv-CD Dataset](https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLII-2/565/2018/isprs-archives-XLII-2-565-2018.pdf)


The data folder is structured as follows:

```
├── data/
│   ├── levir_CD/    # Levir-CD dataset
|   |   ├── train/    # traning set 
|   |   |   ├── t1/    #images of time t1
|   |   |   ├── t2/    #images of time t2
|   |   |   ├── label/    #ground truth
|   |   ├── val/    # validation set
|   |   |   ├── t1/
|   |   |   ├── t2/
|   |   |   ├── label/
|   |   ├── test/    # testing set
|   |   |   ├── t1/
|   |   |   ├── t2/
|   |   |   ├── label/    #ground truth for evaluation
|   |   ├── results/    # path to save the model
│   ├── SVCD/
|   |   ├── leveb/    # Lebediv-CD dataset, have the same structure of the Levir-CD dataset
...
```


## Citation

The paper was submitted to ISPRS Journal.
