<img src='https://productfile.cupoy.com/cvdl/1592637697737/large'>

# 1. 基礎影像處理
> 學習影像處理基礎，並熟悉 OpenCV 寫作方式以及如何前處理

1. [OpenCV 簡介 + 顯示圖片](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day001_read_image_HW.ipynb) — 入門電腦視覺領域的重要套件: OpenCV
2. [Color presentation 介紹 (RGB, LAB, HSV)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day002_change_color_space_HW.ipynb) — 淺談圖片不同的表示方式
3. [顏色相關的預處理 (改變亮度, 色差)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day003_color_spave_op_HW.ipynb) — 透過圖片不同的表示方式實作修圖效果
4. [以圖片為例做矩陣操作 (翻轉, 縮放, 平移)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day004_geometric_transform_HW.ipynb) — 淺談基礎的幾合變換: 翻轉 / 縮放 / 平移
5. [透過 OpenCV 做圖並顯示 (長方形, 圓形, 直線, 填色)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day005_draw_HW.ipynb) — 實作 OpenCV 的小畫家功能
6. [affine transformation 概念與實作](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day006_affine_HW.ipynb) — 仿射轉換的入門與實作: affine transform
7. [perspective transformation 概念與實作](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day007_perspective.ipynb) — 視角轉換的入門與實作: perspective transform
8. [Filter 操作 (Sobel edge detect, Gaussian Blur)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day008_sobel_gaussian_blur_HW.ipynb) — 初探邊緣檢測與模糊圖片操作: 了解 filter 的運用
9. [SIFT 介紹與實作 (feature extractor)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day009_sift.ipynb) — SIFT: 介紹與實作經典的傳統特徵
10. [SIFT 其他應用 (keypoint matching)](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day010_sift_brute_force_match.ipynb) — SIFT 案例分享: 特徵配對

# 2. 電腦視覺深度學習基礎
> 打好卷積神經網路的概念，並了解 CNN 各種代表性的經典模型
11. [CNN分類器架構：卷積層](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day011_CNN-count_parameter_HW.ipynb) — 卷積是CNN的核心，了解卷積如何運行 就能幫助我們理解CNN的原理
12. [CNN分類器架構：步長、填充](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day012_Strides%20and%20Padding_HW.ipynb) — 填充與步長是CNN中常見的超參數， 了解如何設置能幫助我們架構一個CNN Model
13. [CNN分類器架構：池化層、全連接層](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day013_Pooling_HW.ipynb) — 池化層時常出現於CNN結構中，而FC層則會接在模型輸出端， 了解如兩者用途能幫助我們架構一個CNN Model
14. [CNN分類器架構：Batch Normalization](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day014_Batch%20Normalization_HW.ipynb) — Batch Normalization出現在各種架構中， 了解BN層能解決怎樣的問題是我們本章的重點
15. [訓練一個CNN分類器：Cifar10為例](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day015_Cifar_HW.ipynb) — 綜合上述CNN基本觀念， 我們如何結合這些觀念打造一個CNN 模型
16. [如何使用Data Augmentation](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day016_Image%20Augmentation_HW.ipynb) — 訓練模型時常常會遇到資料不足的時候，適當的使用Image Augmentation能提升模型的泛化性
17. [深度學習理論與實作：Classic CNN Backbone](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day018_Vgg16_HW.ipynb) — 綜合之前所學的CNN觀念，認識第一個引領影像研究方向朝向深度學習的模型
18. 同上
19. [InceptionV1-V3](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day019_Inception_HW.ipynb) — Inception module提供大家不同於以往的思考方式，將模型的參數量減少，效能卻提升了許多
20. [ResNetV1-V2、InceptionV4、Inception-ResNet](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day020_Classic%20CNN-ResNet%E3%80%81InceptionV4%E3%80%81Inception-ResNet_HW.ipynb) — 首次超越人類分類正確率的模型，Residual module也影響了後來許多的模型架構
21. [Transfer learning](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day021_Transfer%20Learning_HW.ipynb) — 學習如何利用前人的知識輔助自己訓練與跨領域學習的方法
22. [Breaking Captchas with a CNN](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day022_Captcha_HW.ipynb) — 了解如何使用CNN+CTC判定不定長度字串

# 3. CNN 應用案例學習
23. [Object detection原理](https://github.com/eatPizza311/DL-CV_Marathon/blob/main/homework/Day023_OD_theory_HW.ipynb) — 了解Object Detection出現的目的與基本設計原理
