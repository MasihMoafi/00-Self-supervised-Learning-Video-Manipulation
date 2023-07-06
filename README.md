## First order model and Co-segmentation-based Video Editing Project

### Acknowledgements

This project is based on the research paper, "Motion Supervised co-part Segmentation," by Aliaksandr Siarohin and his team, and extensively uses the code from the motion-cosegmentation repository. The original code and repository can be found here. https://github.com/AliaksandrSiarohin/motion-cosegmentation/tree/master. For the first-order-model demo refer to:
https://colab.research.google.com/github/AliaksandrSiarohin/first-order-model/blob/master/demo.ipynb?authuser=1#scrollTo=Oxi6-riLOgnm

### Description

The project's aim was to adapt this codebase to a unique application: creating a custom video editing pipeline to swap specific parts in a video (e.g., eyes, hair, and lips) using the co-segmentation method and face-swapping using the First order motion model. The custom application allowed us to identify and change specific features in video sequences, given an input source image.

    "First Order Motion Model for Image Animation": This model is used to animate still images based on a driving video. The model employs a self-supervised approach to learn the motion dynamics from unlabeled videos. It then applies these dynamics to animate novel images.

    "Motion Co-segmentation": The method performs co-segmentation, i.e., it separates the foreground and background, taking into account the motion of the foreground object. This allows for more accurate segmentation in the presence of similar colors or textures in the foreground and background.

This project was undertaken over a span of a week and was successfully executed on a local machine. During the process, several issues were encountered and resolved, providing rich learning experience on deploying deep learning models, handling dependencies, troubleshooting errors, and enhancing the performance.

### Prerequisites

The project was executed on a local machine with the following specifications:

    Python 3.8.10
    CUDA 11.3
    torch 1.10.0
    scikit-image 0.18.0
    
### Results

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/d3cbec66-2d60-4b58-afda-272bb459a1d7
![crazy](https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/16f864b3-62e6-47d4-9f2f-4de5b0786bba)


https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/1552acbb-7845-4c34-ac8d-8242762b14f0


https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/faba3824-2743-4fc0-b0af-59d81126eb69

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/595fa98b-ef62-452d-9f4f-0b8cda3ab999

The result of the project is a video sequence where specified parts (as per the swap index) are replaced with corresponding parts from the source image. The performance of the result can vary based on the source image and video used, and the mo

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/14a311ab-dab7-467f-9302-d8da95b2ea6f

del's ability to identify the parts to be replaced.



https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/b89bfae2-6bc5-4456-b827-d3f229eaf17a



