Credit to kazmiekr, https://github.com/kazmiekr
I got this code from him, and tried to modify his code for other types of seven-segment images.

# Gas Pump OCR

Project for attempting to scan pictures of gas pumps and detect the digits in the cost and fuel amount displays. Operating under the assumption that most pumps use a 7 segment digit display.

## Dependencies

* Python
* OpenCV
* NumPy

## Setup

* install python
* 'pip install opencv' or install using the opencv's source link

## Running

* **playground.py [file_name]** - Used to try out different image manipulation variables, can hardcode an image or pass one in via the command line
* **train_model.py** - Used to take a folder organization of confirmed digits and generate a `knn` training file
* **test_processing.py** - Used to run the trained algorithm on a folder of test images to test accuracy, can also be setup to test all the configurations to determine optimal values
* **generate_distorted_images.py** - Used to take an image or a folder and run a set of image manipulations to create addtional sample images

