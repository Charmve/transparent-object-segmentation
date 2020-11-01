<a href="https://github.com/Charmve" target="_blank">Charmve</a> | English | Chinese

<div align="center">
    <img src="https://github.com/Charmve/Mirror-Glass-Detection/blob/master/logo-GlassDetec.png" width="400px">
</div>

<p align="center">
  <a href="https://github.com/Charmve"><img src="https://img.shields.io/badge/Github-Charmve-blue" alt="github"></a>
  <a href="https://github.com/Charmve/Mirror-Glass-Detection"><img src="https://img.shields.io/badge/Charmve-Glass%20Detect-red" alt="Mirror%20Glass%20Detection"></a>
  
</p>

<br>

# Transparent-Object-Segmentation

Transparent objects such as windows and bottles made by glass widely exist in the real world. Segmenting transparent objects is challenging because these objects have diverse appearance inherited from the image background, making them had similar appearance with their surroundings.
<br>

## Segmenting Transparent Objects in the Wild (ECCV 2020)

Enze Xie, Wenjia Wang, Wenhai Wang, Mingyu Ding, Chunhua Shen, Ping Luo

<strong>Abstract</strong>

Transparent objects such as windows and bottles made by glass widely exist in the real world. Segmenting transparent objects is challenging because these objects have diverse appearance inherited from the image background, making them had similar appearance with their surroundings. Besides the technical difficulty of this task, only a few previous datasets were specially designed and collected to explore this task and most of the existing datasets have major drawbacks. They either possess limited sample size such as merely a thousand of images without manual annotations, or they generate all images by using computer graphics method (i.e. not real image). To address this important problem, this work proposes a large-scale dataset for transparent object segmentation, named Trans10K, consisting of 10,428 images of real scenarios with carefully manual annotations, which are 10 times larger than the existing datasets. The transparent objects in Trans10K are extremely challenging due to high diversity in scale, viewpoint and occlusion as shown in Fig. 1. To evaluate the effectiveness of Trans10K, we propose a novel boundary-aware segmentation method, termed TransLab, which exploits boundary as the clue to improve segmentation of transparent objects. Extensive experiments and ablation studies demonstrate the effectiveness of Trans10K and validate the practicality of learning object boundary in TransLab. For example, TransLab significantly outperforms 20 recent object segmentation methods based on deep learning, showing that this task is largely unsolved. We believe that both Trans10K and TransLab have important contributions to both the academia and industry, facilitating future researches and applications.

<strong>Related Material</strong>

[<a href="https://arxiv.org/pdf/2003.13948v3.pdf" target="_blank">pdf</a>] [<a href=" ">supp</a>] [<a href="https://github.com/xieenze/Segment_Transparent_Objects" target="_blank">code</a>]
<br>

## Deep Polarization Cues for Transparent Object Segmentation (CVPR 2020)

Agastya Kalra, Vage Taamazyan, Supreeth Krishna Rao, Kartik Venkataraman, Ramesh Raskar, Achuta Kadambi; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2020, pp. 8602-8611

<strong>Abstract</strong>

Segmentation of transparent objects is a hard, open problem in computer vision. Transparent objects lack texture of their own, adopting instead the texture of scene background. This paper reframes the problem of transparent object segmentation into the realm of light polarization, i.e., the rotation of light waves. We use a polarization camera to capture multi-modal imagery and couple this with a unique deep learning backbone for processing polarization input data. Our method achieves instance segmentation on cluttered, transparent objects in various scene and background conditions, demonstrating an improvement over traditional image-based approaches. As an application we use this for robotic bin picking of transparent objects.

<strong>Related Material</strong>

[<a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Kalra_Deep_Polarization_Cues_for_Transparent_Object_Segmentation_CVPR_2020_paper.pdf" target="_blank">pdf</a>] [<a href="https://openaccess.thecvf.com/content_CVPR_2020/supplemental/Kalra_Deep_Polarization_Cues_CVPR_2020_supplemental.pdf" target="_blank">supp</a>] [<a href="">code</a>] [<a href="https://www.youtube.com/watch?v=hF64LfsR5Lc" target="_blank">video</a>] 
<br>


## Single-Stage Semantic Segmentation from Image Labels (CVPR 2020)

Nikita Araslanov and Stefan Roth

<strong>Abstract</strong>

Recent years have seen a rapid growth in new approaches improving the accuracy of semantic segmentation in a weakly supervised setting, i.e. with only image-level labels available for training. However, this has come at the cost of increased model complexity and sophisticated multi-stage training procedures. This is in contrast to earlier work that used only a single stage − training one segmentation network on image labels − which was abandoned due to inferior segmentation accuracy. In this work, we first define three desirable properties of a weakly supervised method: local consistency, semantic fidelity, and completeness. Using these properties as guidelines, we then develop a segmentation-based network model and a self-supervised training scheme to train for semantic masks from image-level annotations in a single stage. We show that despite its simplicity, our method achieves results that are competitive with significantly more complex pipelines, substantially outperforming earlier single-stage methods.

<strong>Related Material</strong>

[<a href="https://arxiv.org/abs/2005.08104" target="_blank">arXiv</a>] [<a href="" target="_blank">supp</a>] [<a href="https://github.com/visinf/1-stage-wseg" target="_blank">code</a>]
<br>


## TransCut: Transparent Object Segmentation from a Light-Field Image (ICCV 2015)

Yichao Xu, Hajime Nagahara, Atsushi Shimada, Rin-ichiro Taniguchi
Kyushu University, Japan

<strong>Abstract</strong>

The segmentation of transparent objects can be very useful in computer vision applications. However, because they borrow texture from their background and have a similar
appearance to their surroundings, transparent objects are not handled well by regular image segmentation methods. We propose a method that overcomes these problems using the consistency and distortion properties of a light-field image. Graph-cut optimization is applied for the pixel labeling problem. The light-field linearity is used to estimate
the likelihood of a pixel belonging to the transparent object or Lambertian background, and the occlusion detector is used to find the occlusion boundary. We acquire a light
field dataset for the transparent object, and use this dataset to evaluate our method. The results demonstrate that the proposed method successfully segments transparent objects from the background.

<strong>Related Material</strong>

[<a href="https://arxiv.org/pdf/1511.06853v1.pdf" target="_blank">arXiv</a>] [<a href="" target="_blank">supp</a>] [<a href="" target="_blank">code</a>]


## Mirror & Glass Detection in Real Scene

repo：https://github.com/Charmve/Mirror-Glass-Detection
