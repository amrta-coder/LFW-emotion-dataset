# LFW emotion dataset

The dataset download link: [LFW-emotion-dataset](https://drive.google.com/file/d/1vM3qHpZ6PcrU9UGwEbnAYl-gmh-rOw2r/view?usp=sharing)

The related paper can be found from here: [Facial Expression Recognition with the advent of face masks](https://www.researchgate.net/publication/346519054_Facial_Expression_Recognition_with_the_advent_of_face_masks)

The presentation video can be found from here: [Facial Expression Recognition with the advent of face masks - MUM2020 presentation](https://www.youtube.com/watch?v=sWHEfynf5jA)

LFW emotion dataset is annotated based on [LFW](http://vis-www.cs.umass.edu/lfw/) (Labeled Faces in the Wild).

This dataset consists of two parts and can be used for the following study:

* **LFW-FER:**  LFW dataset annoteted manually for facial expression recoginition study.
* **M-LFW_FER:**  LFW dataset processed by automatic wearing face mask method for masked facial expression recoginition study.


## License
**Only the usage of LFW emotion dataset (both LFW-FER and M-LFW-FER) for academic/non-commercial purpose is permitted.**


## LFW-FER dataset

LFW-FER denotes LFW dataset annoteted for facial expression recoginition study.

We manually annotate LFW dataset according to three types of facial expressions (positive, negative, neural), which contain five types of facial orientations (up, left, center, right, down).

Some pictures, difficult to distinguish expression, are removed and 10487 out of 13000 samples are selected from LFW to obtian a LFW-FER dataset finally.

<div align="center"><img src="./LFW-FER-sample.png" width="480px"></div>


## M-LFW-FER dataset

LFW-FER denotes LFW dataset processed by automatic wearing face mask method for masked facial expression recoginition study.

<div align="center"><img src="./M-LFW-FER-sample.png" width="480px"></div>


## Citations

If you want to use LFW-FER or M-LFW-FER dataset in your study, please cite as:

```BibTeX
@inproceedings{LFW-emotion,
  author = {Yang, Bo and Wu, Jianming and Hattori, Gen},
  title = {Facial Expression Recognition with the advent of human beings all behind face masks},
  year = {2020},
  publisher = {Association for Computing Machinery},
  address = {Essen, Germany},
  series = {MUM2020}
}
```
You can find the paper from: https://dl.acm.org/doi/10.1145/3428361.3432075

As LFW is a base work, you are also recommended to cite the following:


```BibTeX
@TechReport{LFWTech,
  author = {Gary B. Huang and Manu Ramesh and Tamara Berg and Erik Learned-Miller},
  title = {Labeled Faces in the Wild: A Database for Studying Face Recognition in Unconstrained Environments},
  institution = {University of Massachusetts, Amherst},
  year = {2007},
  number = {07-49},
  month = {October}
}
```

## Contact

Questions and comments can be sent to:

Jianming Wu(ji-wu@kddi-research.jp) or Bo Yang(bo-yang@kddi-research.jp)

## Related works

### LFW emotion dataset is also used in the following works:

1. [Face Mask Aware Robust Facial Expression Recognition During The Covid-19 Pandemic](https://www.researchgate.net/publication/353234909_Face_Mask_aware_Robust_Facial_Expression_Recognition_during_the_COVID-19_Pandemic)

```BibTeX
@Inproceedings{masked-FER,
  author    = {Yang, Bo and Jianming, Wu and Hattori, Gen},
  booktitle = {2021 IEEE International Conference on Image Processing (ICIP)}, 
  title     = {Face Mask Aware Robust Facial Expression Recognition During The Covid-19 Pandemic}, 
  year      = {2021},
  volume    = {},
  number    = {},
  pages     = {240-244},
  doi       = {10.1109/ICIP42928.2021.9506047}
}
```

2. [Occlusion aware Facial Landmark Detection based Facial Expression Recognition with Face Mask](https://www.researchgate.net/publication/349549226_Occlusion_aware_Facial_Landmark_Detection_based_Facial_Expression_Recognition_with_Face_Mask)

```BibTeX
@Techreport{FLD-FER-masked,
   author       = {Bo, Yang and Jianming, Wu and Gen, Hattori},
   title        = {Occlusion aware Facial Landmark Detection based Facial Expression Recognition with Face Mask},
   year         = {2021},
   institution  = {KDDI Research, Inc.},
   number       = {4},
   month        = {feb}
}
```

```BibTeX
@Article{FMA-FER,
   author = {Bo Yang and Jianming Wu and Kazushi Ikeda and Gen Hattori and Masaru Sugano and Yusuke Iwasawa and Yutaka Matsuo},
   title = {Face-mask-aware Facial Expression Recognition based on Face Parsing and Vision Transformer},
   journal = {Pattern Recognition Letters},
   volume = {164},
   pages = {173-182},
   year = {2022},
   issn = {0167-8655},
   doi = {https://doi.org/10.1016/j.patrec.2022.11.004},
}
```
