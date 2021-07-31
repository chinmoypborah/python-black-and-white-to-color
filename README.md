# python-black-and-white-to-color
Created a Python Program that uses OpenCV, NumPy, and Argparse modules. It is a simple tool that can convert any black and white photo into color on a single command.
This program uses models colorization_deploy_v2.prototxt, colorization_release_v2.caffemodel and pts_in_hull.npy

You need a file named "colorization_release_v2.caffemodel" for working of this script.
Download the file from here: https://drive.google.com/file/d/1DeMfbJ9f3mgAQHGA4mWglxKBmBVOKgcJ/view?usp=sharing

Usage:
python bc.py -i [filename]
