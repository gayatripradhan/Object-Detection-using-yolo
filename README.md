# Object-Detection-using-yolo
This repository will help you to detect multiple objects in a video and it also gives privelege to detect one particular object in a video as well. \
Download the pre-trained YOLO weights from this [link](https://drive.google.com/drive/folders/1OF3MJGXVZKgDZ9f4E--3JH0AJdC6Sk2o?usp=sharing) and save it in the yolo-coco folder.\
You can download other YOLO models and its corresponding cfg file from [YOLO website](https://pjreddie.com/darknet/yolo/) as well.

# Running the script

- **Run detection for all objects in the video**
> python demo.py --input street.mp4 --output output/all_output.avi --yolo yolo-coco --lable all <br/>
Output:
![ouput](https://github.com/gayatripradhan/Object-Detection-using-yolo/blob/master/pictures/all.PNG)
 
- **Run detection for a particular class (eg: person/car)**

> python demo.py --input street.mp4 --output output/person_output.avi --yolo yolo-coco --lable person <br/>
Output
![ouput](https://github.com/gayatripradhan/Object-Detection-using-yolo/blob/master/pictures/people.PNG) <br/>

> python demo.py --input street.mp4 --output output/car_output.avi --yolo yolo-coco --lable car <br/>
 Output 
![output](https://github.com/gayatripradhan/Object-Detection-using-yolo/blob/master/pictures/car.PNG) <br/>

Similary, you can detect any object from the list of classes mentioned in yolo-coc/coco.names file.
