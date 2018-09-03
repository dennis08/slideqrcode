# slideqrcode
using NVIDIA Jetson to scan and recoganize multi qrcode

# Environment
Jetson TX1/2
JetPack3.1 ~ 3.3
Python+OpenCV+pyzbar

# Content
Realtime video qrcode capture and recognize using barcode_scan_video_tx2.py
python barcode_scan_video_tx2.py  (open camera /dev/video0&1)

Static image qrcode capture and recognize using barcode_scan_image_tx2.py
python barcode_scan_image_tx2.py QRCodeImage/Text.png 
