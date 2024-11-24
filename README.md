# OPENCV PROJECTS


## GRAB CUT ALGORITHM FOR BACKGROUND REMOVAL

- When the rectangle is drawn around the ROI in the image the grab cut algorithm considers everything outside the rectangle as background and inside the rectangle as unknown.<br/>
- The algorithm then labels the foreground and background pixels and used a gaussian  mixture model(GMM) to foreground and background.<br/>
- The GMM learns and creates the new pixel distribution. A graph is built and every foreground is connected to source node and background to the sink node<br/>
- A mincut algorithm is used to segment the graph and then all the nodes connected to source node become foreground and that to sink node become background.<br/>
- The process continues until the classification converges.<br/> 
<p float = "left">
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Background_removal_grabcut_algo/images/mask.jpg" width = 200 title ="Mask" hspace="20" /><img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Background_removal_grabcut_algo/images/mask2.jpg" width = 200 title = "Mask2" hspace="20" /><img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Background_removal_grabcut_algo/images/finalimage.jpg" width = 200 title= "final" hspace="20" />
</p>


## OCR Text Detection using Pytesseract

- Here I have implemented OCR text detection using pytesseract the workflow of pytesseract is as follows.<br/>
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/OCR_text_detection/images/workflow.png"><br/>
- The output for OCR text detection<br/>
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/OCR_text_detection/images/output.png" width = 400 title = "OCR image"><br/>


## Barcode and QR code generation and reading

- Here we detect the barcode and QR code and generate them as well.<br/>
- Sample barcode generated<br/>
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/barcode_QR_generation_reading/images/output1.png" width = 300><br/>
- QR code structure<br/>
<img src = "https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/QR_Code_Structure_Example_3.svg/800px-QR_Code_Structure_Example_3.svg.png" width = 300><br/>
- QR code detection<br/>
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/barcode_QR_generation_reading/images/output.png" witdh = 200 height = 300><br/>


## Neural Style Transfer

- Neural Style Transfer enables the artistic style of an image to be applied to another image! It copies the color patterns, combinations, and brush strokes of the original source image and applies it to your input image. And is one the most impressive implementations of Neural Networks in my opinion.<br/>
<img src ="https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Neural_style_transfer/output/workflow.png" width = 500><br/>
-The results after implmentation on the astronaut image are as follows:<br/>
<p float = "left">
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Neural_style_transfer/output/starry_night.png" width = 400 title ="Mask" hspace="20" /><img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Neural_style_transfer/output/wave.png" width = 400 title = "Mask2" hspace="20" /><img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Neural_style_transfer/output/composition.png" width = 400 title= "final" hspace="20" /><img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Neural_style_transfer/output/mosaic.png" width = 400 title= "final" hspace="20" />
</p>
-The result after implementing neural style transfer on video are as follows:<br/>
<img src ="https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Neural_style_transfer/output/video.gif" width = 400><br/>
