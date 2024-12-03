# 🔍Fairness Analysis for Face Verification 

This repository provides the fair dataset of synthetic faces created in the paper **Fairer Analysis and Demographically Balanced Face Generation for Fairer Face Verification** published at WACV 2025 (see [credits](#-acknowledgments-and-credits)). We plan to release the code to generate other synthetic datasets.

If you are rather interested by tools for conducting a comprehensive fairness analysis of face verification models, look at [this repository](https://github.com/MSoumm/FaVFA) or [this one](https://github.com/CEA-LIST/FaVFA) (both should be the same).

# Dataset
The dataset can be found [here](https://1drv.ms/f/c/c452783a8b2f31f6/EqlQKhaeU1lNnZkaDEw8MI0BAz4HbnFzFmvsc3ecy1S-IA?e=bI4uaJ)

It has a size and structure comparable to previous training sets of face verification models sucha s [digiface-1m](https://github.com/microsoft/DigiFace1M), [SynFace](https://github.com/haibo-qiu/SynFace) or [CASIAWebFace](https://www.kaggle.com/datasets/debarghamitraroy/casia-webface). More precisely it contains:
* 10,000 unique identities
* 50 image per identity thus 500,000 image in total

Images were balanced with regards to four attributes, namely *gender* (2 classes), *ethnicity* (4 classes), *age* (continuous) and  *pose* (three continuous angles).

# 🙌 Acknowledgments and Credits
Special thanks to the developers of [DCFace](https://github.com/mk-minchul/dcface/) and [FairFace](https://github.com/joojs/fairface) for their invaluable tools and resources.

If you find this work useful and use it on your own research, please cite our paper
```
@inproceedings{afm2025fairer_analysis,
  author = {Fournier-Montgieux, Alexandre and Soumm, Michael and Popescu, Adrian and Luvison, Bertrand and Le Borgne, Herv{\'e}},
  title = {Fairer Analysis and Demographically Balanced Face Generation for Fairer Face Verification},
  booktitle = {Winter Conference on Applications of Computer Vision (WACV)"},
  address = "Tucson, Arizona, USA",
  year = {2025},
}
```


