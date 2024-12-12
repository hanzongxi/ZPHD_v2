### Download the ZPHD_v2 database

The ZPHD_v2 (Zoom PHoto Database version2) is our latest version of  zoom photo quality database, which can be downloaded at [[Baidu Drive]](https://pan.baidu.com/s/1hev1g3m3UerMZekZZf_ICQ),  password: zphd

Currently, this ZPHD_v2 contains about 1200 zoom photos taken simiultaneously by 30 phone uints shooting in 40 scenes of three zoom times 2X(22), 3X(8), 5X(10). It is meant to compare the zoom capability of different mobile cameras. **Compared to our previous work [2], the image number increase from 900 to 1200, and the rating method transfers from single stimulus to the improved anchor ruler method with expert rank orders. Thus, the MOS distribution and specific MOS for an image have changed。**

The folder is named as "the zoom times+scene number", without the plus symbol. For example, 5XZOOM1 includes 5X zoom photos of the first scene. Each subfolder contains about 30 phones shooting in a scene simultaneously so that we can compare their zoom quality directly. During the shooting process, we shoot at least three consecutive photos for each phone. The best composited one with less occlusions is picked for this database. The phone models are listed as follows:

iPhone6sPlus, 7Plus, 8, Xs; OPPO FindX2Pro, Reno10X; OnePlus6, 6T, 7Pro, 7TPro; Xiaomi8, CC9Pro; Redmi Note8Pro, K20Pro;  Pixel2, 3, 3a;  Huawei P20Pro, Mate20, HonorV20, 9X;  Galaxy S10, S20+; Lenovo Z6pro; IQOO Neo855; HTC U12+; Sony Xperia1; Meizu16th; SmartisanPro2s; Nokia9PureView; NubiaX.

There are a few shots missing from the ZPHD_v2, such as the the photo of Xiaomi8 in 3XZOOM6 folder, the photo of Xperia1 in 5XZOOM7 folder, etc. Most of them are out-of-focus, and therefore deleted. More photos from cameras such as HTC U11, Galaxy Note8, S7 are in preparation, and may be added to this database in the future.

Also inclued in this database are the expert rank orders and mean opinion scores. The expert rank orders were obtained using the prior hardware information, and the insertion sort algorithm by three experts [1,3]. The mean opinion scores were obtained by the **improved anchor ruler method** based on expert rank orders. The improved anchor ruler method means that our anchors  are chosen from different zoom scenes (vs. the same scene in [1]), since the 100 (approx. 96-98) comes from top performers of 2X zoom scene and the 0 ( approx. 2-4) comes from the worst picture of 5X zoom scene.

If you want to use this database for academic research, please make sure **all** papers below are cited. **For any other purposes, permissions must be required from all the authors. All rights are reserved.** If having any questions, please contact zongxihan@sjtu.edu.cn

[1] Z. Han, R. Xie Blind quality assessment of night-time photos: a region selective approach.

[2] Z. Han, Y. Liu, R. Xie, G. Zhai Image quality assessment for realistic zoom photos. Sensors

[3] Z. Han Research of photo quality assessment on mobile ends. [PhD thesis](https://pan.baidu.com/s/1_6jokzTLIsSOm4kIrmB0xg?pwd=qmug), SJTU. Supervisor: Prof. Guangtao Zhai (*Distinguished Young Scholar of NSFC, IEEE Fellow*)