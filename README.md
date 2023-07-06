### Artificial Intelligence Project for Object and Animal Recognition

By harnessing the power of technologies such as YOLOv3 and OpenCV, I have developed a robust and accurate system for recognizing and identifying objects and animals from images and videos.

### Download the Models file

You have just to run the **getModels.sh** file from command line to download the Yolo needed models file

	sudo chmod a+x getModels.sh
	./getModels.sh
Or, you can download the file by using the command : 
	
  		wget https://pjreddie.com/media/files/yolov3.weights 


### Run the code

Command line usage for object detection using YOLO version 3 

  * Using CPU

    * A video file:
     ```bash
     python3 detect.py --video myvideo.mp4 --device 'cpu'
     ```
    * A single image:
    ```bash
    python3 detect.py --image cat_and_dog.jpg --device 'cpu'
    ```


  * Using GPU

    * A video file:
     ```bash
     python3 detect.py --video myvideo.mp4 --device 'gpu'
     ```
    * A single image:
    ```bash
    python3 detect.py --image cat_and_dog.jpg --device 'gpu'
    ```
You can also use your webcam for object detection. In this case you should not specify a video or image file like:
    ```bash
    	python3 detect.py 
    ```
    
### Results of programme after using an image
<img src = "cat_and_dog_output.jpg" width = 400 height = 300/>
 

### Final Words
The potential applications of this technology are vast and varied, ranging from security and surveillance to robotics. With the rapid advancements in machine learning and computer vision, our system has the ability to enhance decision-making processes, improve efficiency, and contribute to the development of innovative solutions.
