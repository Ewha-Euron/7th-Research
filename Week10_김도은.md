### Paper Details
- **Title**: V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation
- **Authors**:  Fausto Milletari, Nassir Navab, Seyed-Ahmad Ahmadi
- **Conference**: Medical Image Computing and Computer-Assisted Intervention (MICCAI)
- **Year of Publication**: 2015
- **Link**: https://arxiv.org/abs/1606.04797
- **Key Focus**: This paper introduces V-Net, a fully convolutional neural network designed for 3D volumetric medical image segmentation. It processes MRI volumes end-to-end, leveraging volumetric convolutions instead of slice-wise approaches. V-Net adopts a novel loss function based on the Dice coefficient to handle class imbalance between foreground and background voxels, avoiding the need for re-weighted loss functions. The architecture includes a symmetric compression-decompression design with residual learning in each stage to ensure fast convergence and high accuracy. Data augmentation techniques, such as random deformations and histogram matching, enhance training performance on limited datasets. V-Net achieves state-of-the-art results on the PROMISE 2012 dataset for prostate MRI segmentation, providing accurate segmentations in under a second on modern GPUs.
- **Comparison to U-Net**: While U-Net focuses on 2D biomedical image segmentation, V-Net is tailored for 3D volumetric segmentation, making it more suitable for tasks involving MRI and other volumetric data. V-Net's Dice-based loss function and residual learning contribute to its robust handling of imbalanced medical datasets and faster convergence.

### Link
📝 [[논문 리뷰] V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation](https://dony-archive.tistory.com/39)
