# slideqrcode
using NVIDIA Jetson to scan and recoganize multi qrcode

# Environment
Jetson TX1/2
JetPack3.1 ~ 3.3
Python+OpenCV+Pyzbar

# Build
sudo apt-get install libzbar-dev libzbar0
sudo apt-get update; sudo apt-get install python-pip
sudo apt-get install python-numpy
sudo pip install pyzbar
sudo pip install imutils 

# Run
Realtime video qrcode capture and recognize using barcode_scan_video_tx2.py

python barcode_scan_video_tx2.py  (open camera /dev/video0&1)

Static image qrcode capture and recognize using barcode_scan_image_tx2.py

python barcode_scan_image_tx2.py QRCodeImage/Text.png 

# Support
dennis.pub@gmail.com

# Reference 
https://www.pyimagesearch.com/2018/05/21/an-opencv-barcode-and-qr-code-scanner-with-zbar/ 
