
# Image to Poetry

### Image Step:
1. Open a terminal 
2. Install tensorflow ``pip3 install tensorflow``
3. Install OpenCV ``pip3 install opencv-pytho``
4. Install Keras ``pip3 install keras``
5. Install ImageAI ``pip3 install imageai --upgrade``
6. Download the RetinaNet model file that will be used for object detection via this ["link"](https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5).
7. Go to **image** directory and put in a picture in *JPG* format. Rename the image file as **image.jpg**. 
8. Run ``python detection.py`` to see the objects in the picture.

### Poetry Step:
1. Open a terminal
2. Run ``python src/interactive_conditional_samples.py --temperature 1 --top_k 40 --model_name poem``
3. Get the output from the previous step and type it in when you see *Model promt*.
4. Read it out loud and have fun!

## License

[MIT](./LICENSE)
