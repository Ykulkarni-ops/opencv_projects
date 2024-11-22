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


