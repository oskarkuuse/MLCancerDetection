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

We used a tiled dataset and image tiling code [1] to train models. We trained models based on architectures laid out in several papers [2][3][4][5][6][7].



### Citations

1. J. Borovec (2023). Tiled Images dataset (512x512) scale 0.25 all-in-one. Accessed 16.12.2023 https://www.kaggle.com/competitions/UBC-OCEAN/discussion/451908
2. J. Linmans, S. Elfwing, J. Laak, G. Litjens. (2023). Predictive uncertainty estimation for out-of-distribution detection in digital pathology, Medical Image Analysis, Volume 83, https://doi.org/10.1016/j.media.2022.102655.
3. B. Li, Y. Li, K. W. Eliceiri (2021). Dual-stream multiple instance learning network for whole slide image classification with self-supervised contrastive learning. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 14318--14328.
4. Z. Shao, H. Bian, Y. Chen Y. Wang, J. Zhang, X. Ji and others (2021). Transmil: Transformer based correlated multiple instance learning for whole slide image classification. Advances in Neural Information Processing Systems, volume 34, pages 2136--2147.
5. M. H. Daneshvar, H. Sarmadi, K.-V. Yuen (2023). A locally unsupervised hybrid learning method for removing environmental effects under different measurement periods. Measurement, Volume 208, page 112465. https://doi.org/10.1016/j.measurement.2023.112465.
6. M. Ilse, J. Tomczak, M. Welling (2018). Attention-based Deep Multiple Instance Learning. Proceedings of the 35th International Conference on Machine Learning, Volume 80, Pages 2127--2136. http://proceedings.mlr.press/v80/ilse18a/ilse18a.pdf. https://proceedings.mlr.press/v80/ilse18a.html.
7. J. Zhang, X. Zhang, K. Ma, R. Gupta, J. Saltz, M. Vakalopoulou, D. Samaras (2022). Gigapixel Whole-Slide Images Classification Using Locally Supervised Learning. International Conference on Medical Image Computing and Computer-Assisted Intervention, Pages 192--201. Springer.
8. K. J. Alesma (2023). Local Learning for Whole-Slide Image Analysis. Accessed 17.12.2023. https://github.com/karl-joan/local_learning_wsi.