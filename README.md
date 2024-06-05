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
<li><b>YOLOv8 for Clinical Image Segmentation:</b></li><br>
YOLOv8 will be employed for segmentation on the clinical dataset. this task aims to segment and delineate potential cancerous lesions within the clinical images, providing a more precise localization of suspicious areas.
</ol>
