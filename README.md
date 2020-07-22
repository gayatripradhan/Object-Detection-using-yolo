# Object-Detection-using-yolo
Download the pre-trained YOLO weights from this [link](https://drive.google.com/drive/folders/1OF3MJGXVZKgDZ9f4E--3JH0AJdC6Sk2o?usp=sharing) and save it in the yolo-coco folder.

You can download other YOLO models and its corresponding cfg file from this [link](https://pjreddie.com/darknet/yolo/) as well.

# Running the script

- Run detection for all objects in the video
> python demo.py --input street.mp4 --output output/bus_output.avi --yolo yolo-coco --lable all <br/>

Output:
![](https://github.com/gayatripradhan/Object-Detection-using-yolo/blob/master/pictures/all.PNG =250x250)
 
- Run detection for a particular class (eg: person)

> python demo.py --input street.mp4 --output output/bus_output.avi --yolo yolo-coco --lable person<br/>
- ![](https://github.com/gayatripradhan/Object-Detection-using-yolo/blob/master/pictures/people.PNG =250x250) <br/>

> python demo.py --input street.mp4 --output output/bus_output.avi --yolo yolo-coco --lable car<br/>
- ![](https://github.com/gayatripradhan/Object-Detection-using-yolo/blob/master/pictures/car.PNG =250x250)

