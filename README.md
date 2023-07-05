## Co-segmentation-based Video Editing Project


### Acknowledgements

This project is based on the research paper, "Motion Supervised co-part Segmentation," by Aliaksandr Siarohin and his team, and extensively uses the code from the motion-cosegmentation repository. The original code and repository can be found here. https://github.com/AliaksandrSiarohin/motion-cosegmentation/tree/master. For the first-order-model demo refer to:
https://colab.research.google.com/github/AliaksandrSiarohin/first-order-model/blob/master/demo.ipynb?authuser=1#scrollTo=Oxi6-riLOgnm

### Description

The project's aim was to adapt this codebase to a unique application: creating a custom video editing pipeline to swap specific parts in a video (e.g., eyes, hair, and lips) using the co-segmentation method. The custom application allowed us to identify and change specific features in video sequences, given an input source image.

The co-segmentation technique relies on a self-supervised deep learning method. By leveraging motion information inferred from videos, it is able to discover and replace specific parts of objects (in this case, facial features).

This project was undertaken over a span of a week and was successfully executed on a local machine. During the process, several issues were encountered and resolved, providing rich learning experience on deploying deep learning models, handling dependencies, troubleshooting errors, and enhancing the performance.

### Prerequisites

The project was executed on a local machine with the following specifications:

    Python 3.8.10
    CUDA 11.3
    torch 1.10.0
    scikit-image 0.18.0
    
### Results

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/d3cbec66-2d60-4b58-afda-272bb459a1d7

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/faba3824-2743-4fc0-b0af-59d81126eb69

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/595fa98b-ef62-452d-9f4f-0b8cda3ab999

https://github.com/MasihMoafi/NEW---Co-segmentation-/assets/132553157/15ce2296-345b-4b99-ac8a-f92deb61689a

The result of the project is a video sequence where specified parts (as per the swap index) are replaced with corresponding parts from the source image. The performance of the result can vary based on the source image and video used, and the model's ability to identify the parts to be replaced.



