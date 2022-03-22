# ship-datasets
This fine-grained ship classification dataset (FGSC-23) is a 23-category remote sensing ship classification dataset used for research purposes only. There are totally 4080 remote sensing images cropped from Google Earth and GF-2 satellite images and manually annotated by experts. 

Our proposed dataset FGSC-23 has been available at
https://drive.google.com/file/d/1_Y7UtN-Y0v3w4NEMIrdPbg80_05bo9is/view?usp=sharing

This dataset contains two folders: "train" and "test", and 23 subfolders are contained in each folder, where the subfolder name represents the ship-ID. The correspondence between ship-ID and category is listed as follows：
{0:non-ship
1:air carrier
2:destroyer
3:landing craft
4:frigate
5:amphibious transport dock
6:cruiser
7:Tarawa-class amphibious assault ship
8:amphibious assault ship
9:command ship
10:submarine
11:medical ship
12:combat boat
13:auxiliary ship
14:container ship
15:car carrier
16:hovercraft
17:bulk carrier
18:oil tanker
19:fishing boat
20:passenger ship
21:liquefied gas ship
22:barge}

The authors would like to thank Liu Zikun et al. for their help with data and the interpretation on part of the ships. Please cite the following relevant papers when publishing results that use this dataset fully or partly:
Xiaohan Zhang , Yafei Lv , Libo Yao, Wei Xiong, and Chunlong Fu. A New Benchmark and an Attribute-Guided Multilevel Feature Representation Network for Fine-Grained Ship Classiﬁcation in Optical Remote Sensing Images. IEEE Journal of selected topics in applied earth observation and remote sensing, 2020.
Zikun Liu, Liu Yuan, Lubin Weng, et al. A high resolution optical satellite image dataset for ship recognition and some new baselines. Proc. 6th Int. Conf. Pattern Recognit. Appl. Methods, 2017.
