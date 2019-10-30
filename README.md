# BlurDetection
2DHWT implementation using Java (Blur detection)

How to test a image for bluriness ?

0. Locate TwoDMatHaarTests.java in org.vkedco.opencv.haar
1.Make sure you have opencv loaded (change the System.load of libopencv_java244.so to your path and add opencv jar to the project)
2. Set the path of the folder(in which the image is located) in IMG_PATH and IMG_PATH2 strings
3. Set image name in test_edge_detection function in main.
4. Click RUN.

An optional way can be to actually implement the logic behind blur detection by Open CV. It can reduce the apk size greatly.
