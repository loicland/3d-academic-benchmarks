This is a repository for compiling the performances of all computer vision / machine learning / reote sensing papers, published or preprints. This page doubles as a community-sourced bibliography. 

There are so many papers on the subject these days that it can be hard to keep track. So help me out! Add missing papers/banchmarks or correct mistakes through pull requests.

### Shorthands

*OA* : overall 

*mAcc* : mean interclass accuracy

*mIoU* : mean interclass accuracy

*WS* : workshops

By default algorithms are sorted by decreasing mIoU.

# S3DIS
[link](http://buildingparser.stanford.edu/dataset.html)

### 6-fold cross validation

| Shorthand  | Reference | Paper | Published | Code | mIoU| OA | mAcc | 
| ---------- | --------- | ------| --------- | ---- | --- | -- | ---- |
| SSP + SPG | [arXiv](https://arxiv.org/pdf/1904.02113.pdf) | CVPR2019 | [pytorch](https://github.com/loicland/superpoint_graph) | 68.4 | 87.9 | 78.3 | 
| PointCNN | [6] | [arXiv](https://arxiv.org/abs/1801.07791) | Neurips2018 | [tensorflow/pytorch](https://github.com/yangyanli/PointCNN) | 65.4 | 88.1 | 75.6 |
| SPG | [5] | [arXiv](https://arxiv.org/pdf/1711.09869.pdf) | CVPR2018 | [pytorch](https://github.com/loicland/superpoint_graph) | 62.1 | 85.5 | 73.0 |
| Engelmann2018 | [4] | [arXiv](https://arxiv.org/abs/1810.01151) | ECCV2018 WS | - | 58.3 | 84.0 | 67.8 | 
| PointNet++ | [3] | [nips.cc](https://papers.nips.cc/paper/7095-pointnet-deep-hierarchical-feature-learning-on-point-sets-in-a-metric-space.pdf) | Neurips2017 | [tensorflow](https://github.com/charlesq34/pointnet2) | 54.5 | 81.0 | 67.1 |
| Engelmann2017 | [2] | [arXiv](https://arxiv.org/abs/1802.01500) | ICCV2017 WS |- | 49.7 | 81.1 | 66.4 |
| PointNet   | [1] | [arXiv](https://arxiv.org/abs/1612.00593) | CVPR2017 |[tensorflow](https://github.com/charlesq34/pointnet) | 47.6 | 78.5 | 66.2 |


### Area5

| Shorthand  | Reference | Paper | Published | Code | mIoU| OA | mAcc | 
| ---------- | --------- | ------| --------- | ---- | --- | -- | ---- |
| SSP + SPG | [arXiv](https://arxiv.org/pdf/1904.02113.pdf) | CVPR2019 | [pytorch](https://github.com/loicland/superpoint_graph) | 61.7 | 87.9 | 68.2 |
| PCCN | [thecvf.com](http://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Wang_Deep_Parametric_Continuous_CVPR_2018_paper.pdf) | CVPR2018 | - | 58.3 | - | 67.0 |
| SPG | [5] | [arXiv](https://arxiv.org/pdf/1711.09869.pdf) | CVPR2018 | [pytorch](https://github.com/loicland/superpoint_graph) | 58.0 | 86.4 | 66.5 |
| PointCNN | [6] | [arXiv](https://arxiv.org/abs/1801.07791) | Neurips2018 | [tensorflow/pytorch](https://github.com/yangyanli/PointCNN) | 57.3 | 85.9 | 63.9 |
| Engelmann2018 | [4] | [arXiv](https://arxiv.org/abs/1810.01151) | ECCV2018 WS | - | 52.2 | 84.2 | 61.8 |
| PointNet   | [1] | [arXiv](https://arxiv.org/abs/1612.00593) | CVPR2017 |[tensorflow](https://github.com/charlesq34/pointnet) | 41.1 | - | 49.0|

# ScanNet
[link](http://www.scan-net.org/)

| Shorthand  | Reference | Paper | Code | Published | mIoU| OA | mAcc | 
| ---------- | --------- | ------| ---- |---------- | --- | -- | ---- |

# Semantic3d

[link](http://semantic3d.net/)

| Shorthand  | Reference | Paper | Code | Published | mIoU| OA | mAcc | 
| ---------- | --------- | ------| ---- |---------- | --- | -- | ---- |

# KITTI

| Shorthand  | Reference | Paper | Code | Published | mIoU| OA | mAcc | 
| ---------- | --------- | ------| ---- |---------- | --- | -- | ---- |

# vKITTI3d

[link](https://github.com/VisualComputingInstitute/vkitti3D-dataset)

| Shorthand  | Reference | Paper | Code | Published | mIoU| OA | mAcc | 
| ---------- | --------- | ------| ---- |---------- | --- | -- | ---- |



# References

[1] C. R. Qi, H. Su, K. Mo, and L. J. Guibas. Pointnet: Deep learning on point sets for 3d classification and segmentation. In CVPR, 2017

[2] F. Engelmann, T. Kontogianni, A. Hermans, and B. Leibe. Exploring spatial context for 3d semantic segmentation of point clouds. In ICCV Workshops, 2017.

[3] C. R. Qi, L. Yi, H. Su, and L. J. Guibas. PointNet++: Deep hierarchical feature learning on point sets in a metric space. In NIPS, 2017

[4] F. Engelmann, T. Kontogianni, J. Schult, and B. Leibe. Know what your neighbors do: 3d semantic segmentation of point clouds. In GMDL Workshop, ECCV, 2018.

[5] L. Landrieu and M. Simonovsky. Large-scale point cloud semantic segmentation with superpoint graphs. In CVPR. IEEE, 2018.

[6] Y. Li, R. Bu, M. Sun, and B. Chen. Pointcnn: Convolution on X-transformed points. In Neurips, 2018.

[7] S. Wang, S. Suo, W.-C. M. A. Pokrovsky, and R. Urtasun. Deep parametric continuous convolutional neural networks. In CVPR, 2018.

[8] M. Jiang and Y. Wu and T. Zhao and Z. Zhao and C. Lu. PointSIFT: A SIFT-like Network Module for 3D Point Cloud Semantic Segmentation. arXiv, 2018.




