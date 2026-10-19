# SP-IFD: Spatial Prototypes for Few-Shot Image Forgery Detection
Authors：Jianpeng Hou, Xiaofeng Wang, Shanmin Pang
keywords：Few-shot learning, Image forgery detection, Metric learning, Fine-grained classification

```text
SP-IFD/
├── README.md
├── requirements.txt
├── train.py
├── eval.py
├── configs/
│   ├── mini_imagenet.yaml
│   ├── tiered_imagenet.yaml
│   ├── cddb.yaml
│   └── ifcd.yaml
├── datasets/
│   ├── __init__.py
│   ├── mini_imagenet.py
│   ├── tiered_imagenet.py
│   ├── stanford_cars.py
│   ├── stanford_dogs.py
│   ├── cddb.py
│   └── ifcd.py
├── models/
│   ├── backbone.py
│   ├── pafe.py
│   ├── icm.py
│   ├── spatial_prototype.py
│   └── subspace_metric.py
├── losses/
│   ├── cls_loss.py
│   ├── mix_loss.py
│   └── margin_loss.py
├── utils/
│   ├── episode_sampler.py
│   ├── logger.py
│   └── metrics.py
└── scripts/
    ├── train_mini.sh
    ├── train_cddb.sh
    └── eval_cross_domain.sh
