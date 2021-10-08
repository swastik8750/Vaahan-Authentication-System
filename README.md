STEPS TO EXECUTE THE PROJECT-

1. Clone the project in your local system and execute the following commands - 
   $ git clone https://github.com/ultralytics/yolov5
   $ cd yolov5
   $ pip install -r requirements.txt
   
2. detect.py runs inference/detection on a variety of sources.You can run this Project on various streams using the following command-
   $ python detect.py --weights best.pt --source 0  # webcam
                                                 file.jpg  # image 
                                                 file.mp4  # video
                                                 path/  # directory
                                                 path/*.jpg  # glob
                                                 'https://youtu.be/NUsoVlDFqZg'  # YouTube
                                                 'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
                                             
3. auth.xlsx contains the Vehicle Registration Plate which is authorised to take entry in some organisations.
4. After running detect.py, It will store the details about the each and every Vehicles that will go through the system in output.xlsx.
5. Then you can use latest.py which is a GUI built in Pyqt5(Python Library) in which you can enter the Vehicle Registration Plate and it will fetch the following data
   from the system -
   i) Vehicle Registration Plate
   ii) State of Vehicle
   iii) Timing Stamp of Vehicles including Date and Time
   iv) Authorisation status.
