# OCID-Ref: A 3D Robotic Dataset with Embodied Language for Clutter Scene Grounding

![Figure1](./figure1.jpg)

## Introduction
To effectively apply robots in working environments and assist humans, it is essential to develop and evaluate how visual grounding (VG) can affect machine performance on occluded objects. However, current VG works are limited in working environments, such as offices and warehouses, where objects are usually occluded due to space utilization issues. In our work, we propose a novel OCID-Ref dataset featuring an referring expression segmentation task with referring expressions of occluded objects. [OCID-Ref](#) consists of 305,694 referring expressions from 2,300 scenes with providing RGB image and point cloud inputs. To resolve challenging occlusion issues, we argue that it's crucial to take advantage of both 2D and 3D signals to resolve challenging occlusion issues. Our experimental results demonstrate the effectiveness of aggregating 2D and 3D signals but referring to occluded objects still remains challenging for the modern visual grounding systems.

If your have interest in our work, please see our OCID-Ref paper for further details: "[OCID-Ref: A 3D Robotic Dataset with Embodied Language for Clutter Scene Grounding](https://arxiv.org/abs/2103.07679)" by Ke-Jyun Wang, Yun-Hsuan Liu, Hung-Ting Su, Jen-Wei Wang, Yu-Siang Wang, [Winston H. Hsu](https://winstonhsu.info/), [Wen-Chin Chen](http://www.cmlab.csie.ntu.edu.tw/~wcchen/) from [National Taiwan University](https://www.ntu.edu.tw/english/)

## Dataset
#### OCID
First, you must download the fully original RGBD data from [OCID](https://www.acin.tuwien.ac.at/vision-for-robotics/software-tools/object-clutter-indoor-dataset/) to your local.

#### OCID-Ref
The cleaned annotations and referring expressions could download from [GDRIVE](#). (This download link will be available soon!)

## Citation
```
@misc{wang2021ocidref,
      title={OCID-Ref: A 3D Robotic Dataset with Embodied Language for Clutter Scene Grounding}, 
      author={Ke-Jyun Wang and Yun-Hsuan Liu and Hung-Ting Su and Jen-Wei Wang and Yu-Siang Wang and Winston H. Hsu and Wen-Chin Chen},
      year={2021},
      eprint={2103.07679},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## Acknowledgement
This work was supported in part by the Ministry of Science and Technology, Taiwan, under Grant MOST 110-2634-F-002-026 and Qualcomm Technologies, Inc. We benefit from NVIDIA DGX-1 AI Supercomputer and are grateful to the National Center for High-performance Computing. We also thank Yu-Kai Huang for his insightful suggestion on the figures.

## License
The dataset is licensed under MIT license (see [LICENSE](./LICENSE) for details).

