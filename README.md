### Detectron2: Human Pose Estimation and Panoptic Segmentation

**This repository contains a Google Colab notebook demonstrating human pose estimation and panoptic segmentation using Detectron2.**

### Prerequisites
* Python 3.6+
* PyTorch 2.3
* Detectron2
* OpenCV
* NumPy

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/akhileshshinde/detectron2_bodypose_and_panoptic_instance_segmentation.git
   ```
2. Install required packages:
   ```bash
   cd detectron2_bodypose_and_panoptic_instance_segmentation
   pip install -r requirements.txt
   ```

### Usage
1. Open the `Detectron2_bodypose_and_panoptic_instance_segmentation.ipynb` notebook in Google Colab.
2. Replace the image paths with your desired images.
3. Run the notebook to perform human pose estimation and panoptic segmentation.

### Example Images
* **kakade.png:** An example image of my friend Kakade with both body pose estimation applied.
* **kakade_seg.png:** An example image of my friend Kakade with only panoptic segmentation applied.
* **kalpesh_seg.png:** An example image of my friend Kalpesh with only panoptic segmentation applied.
* **me_seg.png:** An example image of myself with only panoptic segmentation applied.

### Models
* **Human Pose Estimation:** COCO-Keypoints/keypoint_rcnn_R_50_FPN_3x.yaml
* **Panoptic Segmentation:** COCO-PanopticSegmentation/panoptic_fpn_R_101_3x.yaml

### Customization
* You can modify the model configurations, image paths, and output settings to suit your specific needs.
* Experiment with different image formats and resolutions.

### Acknowledgments
* This code is based on the Detectron2 library.
* The model weights were obtained from the Detectron2 model zoo.

### License
This project is licensed under the MIT License.

