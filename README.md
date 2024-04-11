# Clustering Propagation for Universal Medical Image Segmentation

>[Clustering Propagation for Universal Medical Image Segmentation](https://arxiv.org/abs/2403.16646) <br>
>[Yuhang Ding](https://scholar.google.com/citations?user=2zbnTq8AAAAJ&hl=en), [Liulei Li](https://scholar.google.com/citations?user=eCrBWngAAAAJ&hl=en), [Wenguan Wang](https://sites.google.com/view/wenguanwang), [Yi Yang](https://scholar.google.com/citations?hl=zh-CN&user=RMSuNFwAAAAJ&view_op=list_works)
>

This is the official implementation of "Clustering Propagation for Universal Medical Image Segmentation" (Accepted at CVPR 2024).

## Abstract

Prominent solutions for medical image segmentation are typically tailored for automatic or interactive setups, posing challenges in facilitating progress achieved in one task to another. This also necessitates separate models for each task, duplicating both training time and parameters. To address above issues, we introduce S2VNet, a universal framework that leverages Slice-to-Volume propagation to unify automatic/interactive segmentation within a single model and one training session. Inspired by clustering-based segmentation techniques, S2VNet makes full use of the slice-wise structure of volumetric data by initializing cluster centers from the cluster results of previous slice. This enables knowledge acquired from prior slices to assist in the segmentation of the current slice, further efficiently bridging the communication between remote slices using mere 2D networks. Moreover, such a framework readily accommodates interactive segmentation with no architectural change, simply by initializing centroids from user inputs. S2VNet distinguishes itself by swift inference speeds and reduced memory consumption compared to prevailing 3D solutions. It can also handle multi-class interactions with each of them serving to initialize different centroids. Experiments on three benchmarks demonstrate S2VNet surpasses task-specified solutions on both automatic/interactive setups.


## Code

Coming soon...

## Citation

If you find this work useful in your research, please star our repository and consider citing:

```
@inproceedings{ding2024s2vnet,
  title={Clustering Propagation for Universal Medical Image Segmentation},
  author={Ding, Yuhang and Li, Liulei and Wang, Wenguan and Yang, Yi},
  booktitle={CVPR},
  year={2024}
}
```

## Contact

Any comments, please email: dyh.ustc.uts@gmail.com.
