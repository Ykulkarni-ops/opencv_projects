# OPENCV PROJECTS


## GRAB CUT ALGORITHM FOR BACKGROUND REMOVAL

When the rectangle as draw around the ROI in the image the grab cut algorithm considers everything outside the rectangle as background and inside the rectangle as unknown.<br/>
The algorithm then labels the foreground and background pixels and used a gaussian  mixture model(GMM) to foreground and background.<br/>
The GMM learns and creates the new pixel distribution. A graph is built and every foreground is connected to source node and background to the sink node<br/>
A mincut algorithm is used to segment the graph and then all the nodes connected to source node become foreground and that to sink node become background.<br/>
The process continues until the classification converges.<br/> 
<p float = "left">
<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Background_removal_grabcut_algo/images/mask.jpg" width = 200/><br/>

<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Background_removal_grabcut_algo/images/mask2.jpg" width = 200/><br/>

<img src = "https://github.com/Ykulkarni-ops/opencv_projects/blob/main/Background_removal_grabcut_algo/images/finalimage.jpg" width = 200/><br/>
</p>
