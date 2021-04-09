# MultiPie Extended Ear Dataset

### Dataset Definition

This dataset was generated from Multi-PIE face dataset [1, 2]. In this repository, we just published image name from Multi-PIE face dataset and detected ear coordinates. You can use face images and corresponding coordinates to obtain ear images.

This dataset is the extended version of [Multi-PIE ear dataset](https://github.com/iremeyiokur/multipie_ear_dataset) [3].

This dataset has been explained and has been used in [our paper](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Biometrics/Yaman_Multimodal_Age_and_Gender_Classification_Using_Ear_and_Profile_Face_CVPRW_2019_paper.pdf). Please cite it, if it is helpful for you.
```
@inproceedings{yaman2019multimodal,
  title={Multimodal Age and Gender Classification Using Ear and Profile Face Images},
  author={Yaman, Dogucan and Irem Eyiokur, Fevziye and Kemal Ekenel, Hazim},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops},
  pages={0--0},
  year={2019}
}
```

### CSV File

CSV file contains following headers:

| Name | Description |
| --- | --- |
| Image Name | Original image name in MultiPie Face dataset |
| ID | Original ID of the corresponding subject in MultiPie Face dataset |
| Label | Subject label for person identification |
| Ear Side | Indicate whether the corresponding ear is left or right one |
| x | x coordinate of the starting point of the bounding box |
| y | y coordinate of the starting point of the bounding box |
| w | Width of the bounding box |
| h | Height of the bounding box |




### References

- [1] Gross, R., Matthews, I., Cohn, J.F., et al.: ‘Multi-PIE’. IEEE Int. Conf. on
Automatic Face and Gesture Recognition (FG), 2008.
- [2] Gross, R., Matthews, I., Cohn, J.F., et al.: ‘Multi-PIE’. Image and Vision
Computing, 2010, pp. 807–813.
- [3] Eyiokur, F.I., Yaman, D., and Ekenel, H.K.: "Domain adaptation for ear recognition using deep convolutional neural networks.", IET Biometrics 7.3 (2017): 199-206.
