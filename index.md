## AID: A Benchmark Dataset for PerformanceEvaluation of Aerial Scene Classification
###Gui-Song Xia, Jingwen Hu, Fan Hu, Baoguang Shi, Xiang Bai, Yanfei Zhong, Xiaoqiang Lu, Liangpei Zhang

##- Abstract -
Aerial scene classification, which aims to automatically label an aerial image with a specific semantic category,is a fundamental problem for understanding high-resolutionremote sensing imagery. In recent years, it has become an activetask in the remote sensing area and numerous algorithms havebeen proposed for this task, including many machine learningand data-driven approaches. However, the existing datasets foraerial scene classification like UC-Merced dataset and WHURS19 are with relatively small sizes, and the results on themare already saturated. This largely limits the development ofscene classification algorithms. This paper describes the AerialImage Dataset (AID): a large-scale dataset for aerial sceneclassification. The goal of AID is to advance the state-of-thearts in scene classification of remote sensing images. For creatingAID, we collect and annotate more than ten thousand aerial sceneimages. In addition, a comprehensive review of the existing aerialscene classification techniques as well as recent widely-used deeplearning methods is given. Finally, we provide a performanceanalysis of typical aerial scene classification and deep learningapproaches on AID, which can be served as the baseline resultson this benchmark.

##AID: a new dataset -[download](https://pan.baidu.com/s/1mifOBv6)
AID is a new large-scale aerial image dataset, by collecting sample images from Google Earth imagery. Note that although the Google Earth images are post-processed using RGB renderings from the original optical aerial images, it has proven that there is no significant difference  between the Google Earth images with the real optical aerial images even in the pixel-level land use/cover mapping. Thus, the Google Earth images can also be used as aerial images for evaluating scene classification algorithms.  

The new dataset is made up of the following 30 aerial scene types: airport, bare land, baseball field, beach, bridge, center, church, commercial, dense residential, desert, farmland, forest, industrial, meadow, medium residential, mountain, park, parking, playground, pond, port, railway station, resort, river, school, sparse residential, square, stadium, storage tanks and viaduct. All the images     are labelled by the specialists in the field of remote sensing image interpretation, and some samples of each class are shown in Fig.1. In all, the AID dataset has a number of 10000 images within 30 classes. 

The images in AID are actually multi-source, as Google Earth images are from different remote imaging sensors. This brings more challenges for scene classification than the single source images like UC-Merced dataset. Moreover, all the sample images per each class in AID are carefully chosen from different countries and regions around the world, mainly in China, the United States,     England, France, Italy, Japan, Germany, etc., and they are extracted at different time and seasons under different imaging conditions, which increases the intra-class diversities of the data. Some samples of each class are shown in Fig.1

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CAPTAIN-WHU/AID/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
