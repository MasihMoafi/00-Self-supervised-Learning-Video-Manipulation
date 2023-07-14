
## Co-segmentation-based Video Editing Project

This project is a custom video editing pipeline that uses co-segmentation and face-swapping techniques to swap specific parts in a video (e.g., eyes, hair, and lips) with corresponding parts from a source image.

### Acknowledgements

This project is based on the research paper, "Motion Supervised Co-part Segmentation" by Aliaksandr Siarohin and his team, and extensively uses the code from the motion-cosegmentation repository.

The project also uses the First Order Motion Model for Image Animation model to animate still images based on a driving video.

### Description

The project's aim was to adapt the motion-cosegmentation codebase to a unique application: creating a custom video editing pipeline to swap specific parts in a video (e.g., eyes, hair, and lips) using the co-segmentation method and face-swapping using the First Order Motion Model. The custom application allowed us to identify and change specific features in video sequences, given an input source image.

The main methods used in this project are:

•  First Order Motion Model for Image Animation: This model is used to animate still images based on a driving video. The model employs a self-supervised approach to learn the motion dynamics from unlabeled videos. It then applies these dynamics to animate novel images.

•  Motion Co-segmentation: The method performs co-segmentation, i.e., it separates the foreground and background, taking into account the motion of the foreground object. This allows for more accurate segmentation in the presence of similar colors or textures in the foreground and background.

This project was undertaken over a span of a week and was successfully executed on a local machine. During the process, several issues were encountered and resolved, providing rich learning experience on deploying deep learning models, handling dependencies, troubleshooting errors, and enhancing the performance.

### Prerequisites

The project was executed on a local machine with the following specifications:

•  Python 3.8.10

•  CUDA 11.3

•  torch 1.10.0

•  scikit-image 0.18.0

### Results

The result of the project is a video sequence where specified parts (as per the swap index) are replaced with corresponding parts from the source image. The performance of the result can vary based on the source image and video used, and the model's ability to identify the parts to be replaced.

Here are some examples of the results:

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/d3cbec66-2d60-4b58-afda-272bb459a1d7

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/1552acbb-7845-4c34-ac8d-8242762b14f0

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/faba3824-2743-4fc0-b0af-59d81126eb69

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/fa95ebba-1602-4303-a555-0d5a0caa14df
