## Semantic-Transferable Weakly-Supervised Endoscopic Lesions Segmentation

This repo contains the source code and dataset for our accepted ICCV 2019 paper:

Semantic-Transferable Weakly-Supervised Endoscopic Lesions Segmentation
2019 IEEE international Conference on Computer Vision (ICCV 2019)

[Paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Dong_Semantic-Transferable_Weakly Supervised_Endoscopic_Lesions_Segmentation_ICCV_2019_paper.pdf) [arXiv](https://arxiv.org/pdf/1908.07669.pdf) 

# Introduction
Weakly-supervised learning under image-level labels supervision has been widely applied to semantic segmentation of medical lesions regions. However, 1) most existing
models rely on effective constraints to explore the internal
representation of lesions, which only produces inaccurate
and coarse lesions regions; 2) they ignore the strong probabilistic dependencies between target lesions dataset (e.g.,
enteroscopy images) and well-to-annotated source diseases
dataset (e.g., gastroscope images). To better utilize these
dependencies, we present a new semantic lesions representation transfer model for weakly-supervised endoscopic
lesions segmentation, which can exploit useful knowledge
from relevant fully-labeled diseases segmentation task to
enhance the performance of target weakly-labeled lesions
segmentation task. More specifically, a pseudo label generator is proposed to leverage seed information to generate
highly-confident pseudo pixel labels by incorporating class
balance and super-pixel spatial prior. It can iteratively include more hard-to-transfer samples from weakly-labeled
target dataset into training set. Afterwards, dynamicallysearched feature centroids for same class among different
datasets are aligned by accumulating previously-learned
features. Meanwhile, adversarial learning is also employed
in this paper, to narrow the gap between the lesions among
different datasets in output space. Finally, we build a
new medical endoscopic dataset with 3659 images collected
from more than 1100 volunteers. Extensive experiments on
our collected dataset and several benchmark datasets validate the effectiveness of our model.

# Datasets
Datasets and source code will be coming soon ...



# Citation
If you find this project useful for your research, please kindly cite our paper:
@InProceedings{Dong_2019_ICCV,
author = {Dong, Jiahua and Cong, Yang and Sun, Gan and Hou, Dongdong},
title = {Semantic-Transferable Weakly-Supervised Endoscopic Lesions Segmentation},
booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
month = {October},
year = {2019}
}





