### AID: A Benchmark Dataset for PerformanceEvaluation of Aerial Scene Classification

** Gui-Song Xia, Jingwen Hu, Fan Hu, Baoguang Shi, Xiang Bai, Yanfei Zhong, Xiaoqiang Lu, Liangpei Zhang **

**- Abstract**

Aerial scene classification, which aims to automatically label an aerial image with a specific semantic category, is a fundamental problem for understanding high-resolution remote sensing imagery. In recent years, it has become an active task in the remote sensing area and numerous algorithms have been proposed for this task, including many machine learning and data-driven approaches. However, the existing datasets for aerial scene classification like UC-Merced dataset and WHU-RS19 are with relatively small sizes, and the results on them are already saturated. This largely limits the development of scene classification algorithms. This paper describes the Aerial Image Dataset (AID): a large-scale dataset for aerial scene classification. The goal of AID is to advance the state-of-the arts in scene classification of remote sensing images. For creating AID, we collect and annotate more than ten thousand aerial scene images. In addition, a comprehensive review of the existing aerial scene classification techniques as well as recent widely-used deep learning methods is given. Finally, we provide a performance analysis of typical aerial scene classification and deep learning approaches on AID, which can be served as the baseline results on this benchmark.

**- AID: a new dataset -[download](https://pan.baidu.com/s/1mifOBv6)**

AID is a new large-scale aerial image dataset, by collecting sample images from Google Earth imagery. Note that although the Google Earth images are post-processed using RGB renderings from the original optical aerial images, it has proven that there is no significant difference between the Google Earth images with the real optical aerial images even in the pixel-level land use/cover mapping. Thus, the Google Earth images can also be used as aerial images for evaluating scene classification algorithms.  

The new dataset is made up of the following 30 aerial scene types: airport, bare land, baseball field, beach, bridge, center, church, commercial, dense residential, desert, farmland, forest, industrial, meadow, medium residential, mountain, park, parking, playground, pond, port, railway station, resort, river, school, sparse residential, square, stadium, storage tanks and viaduct. All the images     are labelled by the specialists in the field of remote sensing image interpretation. In all, the AID dataset has a number of 10000 images within 30 classes. 

The images in AID are actually multi-source, as Google Earth images are from different remote imaging sensors. This brings more challenges for scene classification than the single source images like UC-Merced dataset. Moreover, all the sample images per each class in AID are carefully chosen from different countries and regions around the world, mainly in China, the United States,     England, France, Italy, Japan, Germany, etc., and they are extracted at different time and seasons under different imaging conditions, which increases the intra-class diversities of the data. 

**- Baseline methods- [codes](https://github.com/CAPTAIN-WHU/AID)**
