# Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8
<H2>Datasets</H2>
<ol>
<li><b>Clinical Dataset: </b>This dataset will comprise clinical images of oral lesions for tasks of classification and segmentation.</li>
<li><b>Histopathological Dataset: </b>This dataset will contain histopathological images of oral tissues for classification.</li>
</ol>
<br>
<H3>Classification</H3>
<ol>
<li><b>DINOv2 for Histopathological Image Classification (Transfer Learning):</b><br>
We propose employing DINOv2, a state-of-the-art vision transformer model, for classifying histopathological images. Transfer learning will be utilized by pre-training DINOv2 on a large-scale image dataset and then fine-tuning it on the histopathological dataset for oral cancer classification.</li>
<li><b>YOLOv8 for Clinical Image Classification:</b><br>
YOLOv8, a fast and efficient object detection model, will be used for classifying oral cancer based on clinical images. this approach aims to identify the presence or absence of cancerous lesions within the clinical images.</li>
</ol>
<br>

<H3>Segmentation:</H3>
<ol>
<li><b>YOLOv8 for Clinical Image Segmentation:</b>><br>
YOLOv8 will be employed for segmentation on the clinical dataset. this task aims to segment and delineate potential cancerous lesions within the clinical images, providing a more precise localization of suspicious areas.</li
</ol>

<H3>Evaluation:</H3>

The performance of each model will be evaluated using established metrics appropriate for the respective tasks (classification vs. segmentation). For classification, metrics like accuracy, precision, recall, and F1-score will be used. For segmentation, metrics like Intersection over Union (IOU) and mean Average Precision (mAP) will be employed.

<H3>Dinov2 working Procedure</H3>

![Picture8](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/384b6dbd-087a-4c16-9665-d17f085c77bf)

<H3>YOLOV8 working Procedure</H3>

![Picture9](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/8b322bc1-218b-4be3-ae1f-5c7a5d4e95c6)

<H2>One of the trained batches in classification</H2>

![Picture10](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/6287b9d0-44a5-4c8d-af69-f806718c8f57)

<H2>One of the trained batches in Segmentation</H2>

![Picture11](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/a5dbd327-1aee-4a7d-ac5a-68d5dcdf8aca)

<H2>Predictions made using test set of Histopathology dataset</H2>

![Picture12](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/9a65ede6-8737-465d-9ce6-3c4c6458bae1)

<H2>Confusion Matrices of histopathology and clinical datasets using dinov2</H2>
<br></br>

![Picture13](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/0fd0a765-5bd0-42d8-af2d-3ae25c415f3d)
<br></br>

![Picture14](https://github.com/srinivas21109/Classification-and-Segmentation-of-oral-Cancer-using-DinoV2-and-YOLOV8/assets/119849011/1fd76129-e9e5-46ea-a7ef-8d3277ec839f)



