
## Adaptive Subspaces for Few-Shot Learning
Computer Vision and Patern Recognition 2020.

![img](https://raw.githubusercontent.com/chrysts/chrysts.github.io/master/images/psn.jpg) 


### Requirements:
- PyTorch 1.0 or above
- Python 3.6

There are two backbones separated in different folders. 
- Conv-4, there are two datasets using this backbone: mini-ImageNet and OpenMIC. 
- ResNet-12, there are three datasets using this backbone: mini-ImageNet, tiered-ImageNet, and Cifar-FS.
we use the code provided from https://github.com/kjunelee/MetaOptNet

Run mini-ImageNet:

``` python3 train_subspace_discriminative.py --data-path 'yourdatafolder' ```

Run OpenMIC:

```python3 train_subspace_museum.py --data-path 'yourdatafolder'  ```



Cite:

```
@inproceedings{simon2020dsn,
        author       = {C. Simon}, {P. Koniusz}, {R. Nock}, and {M. Harandi}
        title        = {Adaptive Subspaces for Few-Shot Learning},
        booktitle    = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)}
        year         = 2020
       }
```       
