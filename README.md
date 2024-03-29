# OpenCV-Face-and-Colour-Detection

Based on opencv-python library.

Here are the basic coding for face recognition, and colour detection.


Location for file haarcascade xml:
- rpi: /home/USER/.local/lib/python3.9/site-packages/cv2/data/haarcascade_smile.xml
- windows: C:\Users\USER\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.9_qbz5n2kfra8p0\LocalCache\local-packages\Python39\site-packages\cv2\data
- windows: C:\Users\xtron\AppData\Roaming\Python\Python310\site-packages\cv2\data


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
