# YOLOv5 Object Detection Project

## Project Title

YOLOv5-Based Object Detection using Google Colab

## Short Description

This project demonstrates object detection using YOLOv5 models in Google Colab. The model detects objects from an input image and visualizes the detection results by drawing bounding boxes and confidence scores. The project compares the performance of YOLOv5s and YOLOv5x models and saves the output images with detected objects.

## Tools and Libraries Used

* Python 3
* Google Colab
* PyTorch
* YOLOv5 (Ultralytics)
* OpenCV
* NumPy

## How to Run the Code

1. Open the notebook in Google Colab.
2. Install required packages:

   ```bash
   pip install ultralytics
   ```
3. Run all cells in order.
4. Upload an image when prompted.
5. The model will detect objects and display the results.
6. The output image with bounding boxes will be saved automatically.

## Input Image Description

The input is an image uploaded by the user through Google Colab. The image may contain various objects such as people, cars, chairs, or other common objects from the COCO dataset.

## Output Result Explanation

* The model detects objects in the image.
* Bounding boxes are drawn around detected objects.
* Object names and confidence scores are displayed.
* The final output image is saved as:

  * `output_result1.png` (YOLOv5s result)
  * `output_result2.png` (YOLOv5x result)

## Screenshot / Output Image

Insert the generated output image here.

Example:

![Detection Result](my_detection_result.png)

## License Information

This project is licensed under the MIT License. See the LICENSE file for details.
