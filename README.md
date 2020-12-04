# Color-Detection-Using-OpenCV-
Important notes before you start

1.  You can use any image of your choice. 
2. Make sure you run this program in your terminal or command prompt. 
3. Install all the libraries and APIs required. In this program we will need, OpenCV and Pandas. I also installed NumPy just to get safe. 
Install writing this in your terminal: 

pip install opencv-python numpy pandas

 

If you get an error during the installation of the libraries then make sure you upgrade pip. 
If you get the following error: 
Could not fetch URL https://pypi.python.org/simple/opencv-python/: There was a problem confirming the ssl certificate: [SSL: TLSV1_ALERT_PROTOCOL_VERSION] tlsv1 alert protocol version (_ssl.c:661) - skipping Could not find a version that satisfies the requirement opencv-python (from versions: ) No matching distribution found for opencv-python

Then write the following in your terminal:
pip install –trusted-host files.pythonhosted.org –trusted-host pypi.org –trusted-host pypi-python.org bs4

 

4. Running the program: 
Depending on your python version, you must write:
python3 DetectColor.py -i <image-path>  (for version 3+)
python DetectColor.py -i <image-path>  

 

I would recommend to include the image/images you want to use for this program in your python project file (the file which contains your python script). 

Make sure your python project file compulsorily contains the csv file we are using or else it would show an error. 

5. After running the program, if you hover your mouse over the image, your image will show various RGB values but to know the name of the color you will have to double click on the part of the image you want to know the color of. 
