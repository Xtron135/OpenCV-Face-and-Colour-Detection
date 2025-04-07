# OpenCV-Face-and-Colour-Detection

Based on opencv-python library.

Here are the basic coding for face recognition, and colour detection.


## Simple Tutorial (Windows)
1. Clone this Repo. Download or use git clone. Extract this repo into a folder.

2. Launch Windows Powershell / Terminal / Command Prompt. We recommend using PowerShell.

3. Run:
  ```ShellSession
  python -m pip install --upgrade pip
  ```

  ```ShellSession
  pip3 install opencv-python
  ```

[Optional] If you got "error: externally-managed-environment"
```ShellSession
sudo mv /usr/lib/python3.11/EXTERNALLY-MANAGED /usr/lib/python3.11/EXTERNALLY-MANAGED.old
```

4. Enter this repo folder, and it is now ready to run the example coding. Run
  ```ShellSession
  python3.12 facedetect.py
  ```

  You should be able to see a popup come up using your laptop webcam, highlighting your face.

5. You can play around with the example coding; facedetect.py and colordetect.py. Use code editors like Thonny or Visual Studio to edit the code.

6. OpenCV uses a file called a HAAR Cascade file to recognized and classify objects. There are a few example HAAR Cascade files provided alongside the installation of the OpenCV in your system. You can find it here:

Location for file haarcascade xml:
- rpi: /home/USER/.local/lib/python3.9/site-packages/cv2/data/haarcascade_smile.xml
- windows: C:\Users\USER\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.9_qbz5n2kfra8p0\LocalCache\local-packages\Python39\site-packages\cv2\data
- windows: C:\Users\USER\AppData\Roaming\Python\Python310\site-packages\cv2\data

Simply change the HAAR Cascade file to change the detection criteria. You can also create your own HAAR Cascade file using third-party software to train your own recognition algorithm.


## Reference

1- Open CV installation and Face Detection:
https://towardsdatascience.com/how-to-detect-objects-in-real-time-using-opencv-and-python-c1ba0c2c69c0

2- (Problem) Building wheel for opencv-python took long time (Solution = pip3 install opencv-python==4.5.3.56):
https://stackoverflow.com/questions/63669752/building-wheel-for-opencv-python-pep-517-runs-forever
https://github.com/opencv/opencv-python/issues/391

3- (Problem) libcblas.so.3: cannot open shared object file: No such file or directory:
https://stackoverflow.com/questions/53347759/importerror-libcblas-so-3-cannot-open-shared-object-file-no-such-file-or-dire

4- (Problem) Numpy (Solution = pip install -U numpy)
https://stackoverflow.com/questions/20518632/importerror-numpy-core-multiarray-failed-to-import

5- How to create cascade file:
https://medium.com/@vipulgote4/guide-to-make-custom-haar-cascade-xml-file-for-object-detection-with-opencv-6932e22c3f0e
https://amin-ahmadi.com/cascade-trainer-gui/

6- Open CV Color Detection:
https://www.geeksforgeeks.org/multiple-color-detection-in-real-time-using-python-opencv/
https://www.etutorialspoint.com/index.php/328-python-opencv-specific-color-detction-from-capture-video
https://techvidvan.com/tutorials/detect-objects-of-similar-color-using-opencv-in-python/
