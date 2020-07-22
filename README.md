# Object-Detection-using-yolo
Download the pre-trained YOLO weights from this [link](https://drive.google.com/drive/folders/1OF3MJGXVZKgDZ9f4E--3JH0AJdC6Sk2o?usp=sharing) and save it in the yolo-coco folder.

You can download other YOLO models and its corresponding cfg file from this [link](https://pjreddie.com/darknet/yolo/) as well.

# Running the script

- Run detection for all objects in the video
 python demo.py --input street.mp4 --output output/bus_output.avi --yolo yolo-coco --lable all
 
- Run detection for a particular class (person)
python demo.py --input street.mp4 --output output/bus_output.avi --yolo yolo-coco --lable person
