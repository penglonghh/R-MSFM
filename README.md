# R-MSFM: Recurrent Multi-Scale Feature Modulation for Monocular Depth Estimating(ICCV-2021)
This is the official implementation for testing depth estimation using the model proposed in 
>R-MSFM: Recurrent Multi-Scale Feature Modulation for Monocular Depth Estimating

>Zhongkai Zhou, Xinnan Fan, Pengfei Shi, Yuanxue Xin


R-MSFM can estimate a depth map from a single image.

## R-MSFM Results
![image](https://user-images.githubusercontent.com/32475718/126870917-cac46d69-ab56-482f-911c-d738fe553d3d.png)


## Precomputed results
链接：https://pan.baidu.com/s/18dNi7RCVsGFfxyxKsGXSxA 
提取码：3q28

## Pretrained Model
链接：https://pan.baidu.com/s/1QcCO--ZTokxbj-ly4clgnA 
提取码：ol9r

## KITTI evaluation
You can predict scaled disparity for a single image used R-MSFM3 with:
```shell
python test_simple.py --image_path='path_to_image' --model_path='path_to_model' --update=3
```
or R-MSFM6 with:
```shell
python test_simple.py --image_path='path_to_image' --model_path='path_to_model' --update=6
```
## License & Acknowledgement
The codes are based on [RAFT](https://github.com/princeton-vl/RAFT), [Monodepth2](https://github.com/nianticlabs/monodepth2). Please also follow their licenses. Thanks for their great works.