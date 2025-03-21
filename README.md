# Artiststyle
## Update
Added six classes on January 2, 2024.

Added two classes on November 28, 2023.

Released on November 21, 2023.
## Description
To have a fair comparison with baselines in the context of individual artistic style classification, we created a refined Wikiart dataset, named *Artiststyle* dataset.
- **Size and composition**

The first-edition of *Artiststyle* contains **4055** artwork images collected from **18** artists. Please refer to the [csv.file](https://drive.google.com/file/d/1zhu2xzMs1rBHVRvJqT4MNeJffTs1_eAq/view?usp=drive_link) for more details.

The latest *Artiststyle* contains **5624** artwork images collected from **26** artists.

- **Principle and professionals**

Our research targets on individual artistic styles, so as the classes in *Artiststyle*. Specifically, images belonging to the same category have the same individual artistic style. Therefore, existing datasets like *WikiArt* (containing 52757 images) can not be used directly for training but need to be manually refined. 

For example, 1332 impressionist artworks by *Claude Monet* in *WikiArt* have different artistic styles considering fine-grained factors such as stroke and theme, so we collect 204 sharing the same artistic style from 1332 to form a category in *Artiststyle18*. 

**Five** **experts** who have over **10** years art experience participated in the selection process, during which they selected images according to their artistic styles and authors.
- **Download**

*Artiststyle* and related files can be downloaded [here](https://drive.google.com/drive/folders/1LjEfsn_qd4vITWnUJq8HTjq0OSrSIA-r?usp=drive_link)(Size = 246Mb). We will continue expanding the dataset in the future.
## Note

1. The WikiArt dataset can be used only for non-commercial research purpose.
2. The images in the WikiArt dataset were obtained from WikiArt.org. The authors are neither responsible for the content nor the meaning of these images.
3. By using the WikiArt dataset, you agree to obey the terms and conditions of [WikiArt.org](https://drive.google.com/drive/folders/1LjEfsn_qd4vITWnUJq8HTjq0OSrSIA-r?usp=drive_link).

## Cite  FedStyle

If you find this repository useful, please use the following entry for citation.
```
@INPROCEEDINGS{10688004,
  author={Ran, Changjuan and Guo, Yeting and Liu, Fang and Cui, Shenglan and Ye, Yunfan},
  booktitle={2024 IEEE International Conference on Multimedia and Expo (ICME)}, 
  title={FedStyle: Style-Based Federated Learning Crowdsourcing Framework for Art Commissions}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
  keywords={Crowdsourcing;Art;Costs;Generative AI;Semantics;Collaboration;Contrastive learning;federated learning;contrastive learning;art commissions},
  doi={10.1109/ICME57554.2024.10688004}}
```

## Contributors and Contact

To get a copy of the Conllustration dataset, which is an contemporary illustration dataset containing 3238 artworks, feel free to contact with the author: Changjuan Ran (ChangjuanRan@gmail.com).
