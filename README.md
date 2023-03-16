# YOLO-V3-FUNCTION-CIDE-FOR-VIDEOS
YOLO v3 (You Only Look Once version 3) is a real-time object detection algorithm. It is one of the most popular object detection algorithms because it is fast and accurate. The algorithm can detect objects in images and videos and classify them into different classes.

In this project, we use YOLO v3 to detect objects in videos. The project uses the pre-trained weights of the YOLO v3 algorithm, which have been trained on the COCO dataset. We use OpenCV to read the video frames, detect objects using the YOLO v3 algorithm, and draw bounding boxes around the detected objects.

To run the project, you need to follow these steps:

Download the YOLO v3 pre-trained weights from the following link: https://pjreddie.com/media/files/yolov3.weights

Clone the repository to your local machine.

Install the required libraries. You can install them using the following command:

pip install -r requirements.txt

Run the project using the following command:

python yolo_video_detection.py --input <video_path> --output <output_path> --yolo <yolo_weights_path>

Replace <video_path> with the path of the video you want to detect objects in. Replace <output_path> with the path where you want to save the output video with bounding boxes around the detected objects. Replace <yolo_weights_path> with the path where you downloaded the pre-trained weights of YOLO v3.

For example, if you have a video named "video.mp4" in the same directory as the project, and you want to save the output video as "output.avi" in the same directory, you can run the following command:



python yolo_video_detection.py --input video.mp4 --output output.avi --yolo yolov3.weights

Wait for the project to finish processing the video. The output video will be saved to the path you specified.

That's it! You should now be able to detect objects in videos using YOLO v3. If you have any questions or issues, please refer to the documentation or open an issue on GitHub.







## Screenshots

![App Screenshot](https://infotech.report/Images/Resources/f54e1b5b-de98-4e12-9f6f-4939194047e8_Resources_Real-time-Object.jpg)

