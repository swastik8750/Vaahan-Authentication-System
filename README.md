<b>STEPS TO EXECUTE THE PROJECT-</b>

1. Clone the project in your local system and execute the following commands - </br>
   $ git clone https://github.com/swastik8750/Vaahan-Authentication-System</br>
   $ cd yolov5</br>
   $ pip install -r requirements.txt</br>
   
2. detect.py runs inference/detection on a variety of sources.</br>You can run this Project on various streams using the following command-</br>
   $ python detect.py --<b>weights</b> best.pt </br>--<b>source</b> 0  # webcam</br>
                                                 file.jpg  # image </br>
                                                 file.mp4  # video</br>
                                                 path/  # directory</br>
                                                 path/*.jpg  # glob</br>
                                                 'https://www.youtube.com/watch?v=Z4eOnPTp2Aw'  # YouTube</br>
                                                 'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream</br>
                                             
3. auth.xlsx contains the Vehicle Registration Plate which is authorised to take entry in some organisations.
4. After running detect.py, It will store the details about the each and every Vehicles that will go through the system in output.xlsx.
5. Then you can use latest.py which is a GUI built in Pyqt5(Python Library) in which you can enter the Vehicle Registration Plate and it will fetch the following data
   from the system -
   i) Vehicle Registration Plate
   ii) State of Vehicle
   iii) Timing Stamp of Vehicles including Date and Time
   iv) Authorisation status.
