COMMAND FOR REAL-TIME DETECTION 
yolo.py [-h] [--webcam WEBCAM] [--play_video PLAY_VIDEO]

COMMAND FOR USING IMAGE
yolo.py [-h] [--image IMAGE] [--video_path VIDEO_PATH]
             [--image_path IMAGE_PATH] [--verbose VERBOSE]
COMMAND FOR USING VIDEO 
python yolo.py --play_video True --video_path videos/fire1.mp4

optional arguments:
  -h, --help            show this help message and exit
  --webcam WEBCAM       True/False
  --play_video PLAY_VIDEO
                        Tue/False
  --image IMAGE         Tue/False
  --video_path VIDEO_PATH
                        Path of video file
  --image_path IMAGE_PATH
                        Path of image to detect objects
  --verbose VERBOSE     To print statements