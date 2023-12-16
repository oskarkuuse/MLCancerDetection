# MLCancerDetection
Project for TÜ Machine Learning course.

### Authors
- Karl-Joan Alesma
- Karl Oskar Kuuse
- Randal Annus

### Description

This repository contains code for the kaggle competition UBC Ovarian Cancer Subtype Classification and Outlier Detection (UBC-OCEAN).

The `training` directory contains notebooks used for training models. The `submissions` contains notebooks that were used as submissions to the competition.

The submissions used for the final leaderboard score contain `FINAL` in the notebook name.

We used a tiled dataset and image tiling code [1] to train models. We trained models based on architectures laid out in several papers [2][3][4].



### Citations

1. J. Borovec (2023). Tiled Images dataset (512x512) scale 0.25 all-in-one. Vaadatud 16.12.2023 https://www.kaggle.com/competitions/UBC-OCEAN/discussion/451908
2. J. Linmans, S. Elfwing, J. Laak, G. Litjens. (2023). Predictive uncertainty estimation for out-of-distribution detection in digital pathology, Medical Image Analysis, Volume 83, https://doi.org/10.1016/j.media.2022.102655.
3. B. Li, Y. Li, K. W. Eliceiri (2021). Dual-stream multiple instance learning network for whole slide image classification with self-supervised contrastive learning. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 14318--14328.
4. Z. Shao, H. Bian, Y. Chen Y. Wang, J. Zhang, X. Ji and others (2021). Transmil: Transformer based correlated multiple instance learning for whole slide image classification. Advances in Neural Information Processing Systems, volume 34, pages 2136--2147.



