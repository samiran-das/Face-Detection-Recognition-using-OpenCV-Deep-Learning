# Face-Detection-Recognition-using-OpenCV-Deep-Learning
Implemented Face Detection and thereby Face Recognition Algorithms using OpenCV in Raspberry Pi 3.

Steps to Follow -

✪ Install OpenCV in RPi. To do so watch a video or an article.
✪ Create a folder named as Datasets and create sub folder with the name of the person and put all the front face images of that person in that sub folder. Don't forget to name the sub folder with the name of the person which will be displayed during detection and recognition.
✪ Run the program face_encodings.py with the command given in the very program comment (Top).
✪ You will see a file named as encoded.pickles after the completion. This is the encoded file after the faces are encoded.
✪ Finally run the rpi_face_recognition_main.py program with the command given in the very program comment (Top).

After the Streamer loads you'll find that RPi can detect the person by its name whose faces are given in the datasets folder and for other faces it will promt as unknown.
