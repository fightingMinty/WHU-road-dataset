# WHU-road-dataset 

Update News(2022.10.18)

We just noticed the redirect issue of the hyperlink given in our paper [BT-RoadNet: A boundary and topologically-aware neural network for road extraction from high-resolution remote sensing imagery](https://www.sciencedirect.com/science/article/pii/S0924271620302331?casa_token=7uE43GWTG2YAAAAA:8RsUO2LkhR6gCmU32jkd6KqS6wMU1DSdfXu-A1GOKGRL1_muDYqXuKBEeMQQw10qvPSReJ_s). We are sorry for the inconvenience it caused. There are two new ways to reach our dataset. 

1. When you click the hyperlink (i.e., http://www.lmars.whu.edu.cn/suihaigang/dataset), the browser will direct you to the website http://www.lmars.whu.edu.cn/suihaigang/index. To find the dataset, you need to click "学术成果"->"学术论文" and find the paper "Zhou, Mingting, Haigang Sui, Shanxiong Chen, Jindi Wang, and Xu Chen. "Bt-Roadnet: A Boundary and Topologically-Aware Neural Network for Road Extraction from High-Resolution Remote Sensing Imagery." Isprs Journal of Photogrammetry and Remote Sensing 168 (Oct 2020): 288-306. https://doi.org/10.1016/j.isprsjprs.2020.08.019. [IF 2019 = 7.319][[PDF]][[DataSet]]". Then click the [Dataset]. Finally, you will find the website for the description and the Baidu Netdisk downloading link (Baidu Netdisk: https://pan.baidu.com/s/1UcyMBa8M-peHe8rDz3nRVA, password: WHUR) of The Wuhan University (WHU) Road Dataset.

2. [Baidu Netdisk](https://pan.baidu.com/s/1UcyMBa8M-peHe8rDz3nRVA), password: WHUR

3. [Google Drive](https://drive.google.com/drive/folders/1sBQbOd__VcCWxH5tw5ZM1_hXEjkVB2Uc?usp=sharing)

## The Wuhan University (WHU) Road Dataset

We manually annotated a satellite imagery dataset of roads in Southern China, termed the Wuhan University (WHU) Road Dataset (download from: http://www.lmars.whu.edu.cn/suihaigang/dataset). Images in our dataset are from a variety of satellites including Gaofen-II, WorldView-II and ZY-III, with a spatial resolution at 0.8–2 meters per pixel. Our dataset is located in Liuzhou City, Guangxi Province. The road region annotations in the WHU Road Dataset were labeled by experts in remote sensing image interpretation using ArcGIS software to ensure the quality of the dataset. In urban areas, road types including railways, motorways, primary roads, secondary roads, tertiary roads, and trunk roads were annotated. To simplify annotation, trivial roads such as footways in residential areas were ignored. In rural areas, we labeled roads wider than three meters and longer than five meters. Total area of valid data in our dataset is over 1145 km2. The WHU Road Dataset was cropped into image tiles with the size of 512*512 pixels, with a total number of 6828 samples.

To verify the robustness of road extraction algorithms across region, three large images are also available for downloading. These images are located in three cities in China: Hezhou, Liuzhou, and Nanning. For reasons of privacy protection, the road markings of the three large images cannot be made public for the time being. If you need to evaluate the road extraction results on these three large images, you can email your road extraction results to mintyzhou@whu.edu.cn. Please set the pixel value of the road and the background to 255 and 0 respectively before sending your results. We will report the precision, recall, IoU, accuracy, and F1-score values of your results as soon as possible.

Please note that we do not own the copyrights to the large satellite images. Their use is RESTRICTED to non-commercial research and educational purposes.

## License

This dataset is available for non-commercial scientific research purposes under GNU General Public License v3.0. By downloading and using this dataset you agree to the terms in the LICENSE. 

## Citation

If you use our dataset, please consider citing our work:

[1] Zhou M, Sui H, Chen S, et al. BT-RoadNet: A boundary and topologically-aware neural network for road extraction from high-resolution remote sensing imagery[J]. ISPRS Journal of Photogrammetry and Remote Sensing, 2020, 168: 288-306.

```
@article{zhou2020bt,
  title={BT-RoadNet: A boundary and topologically-aware neural network for road extraction from high-resolution remote sensing imagery},
  author={Zhou, Mingting and Sui, Haigang and Chen, Shanxiong and Wang, Jindi and Chen, Xu},
  journal={ISPRS Journal of Photogrammetry and Remote Sensing},
  volume={168},
  pages={288--306},
  year={2020},
  publisher={Elsevier}
}
```
