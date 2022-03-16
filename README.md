# QR-Code
My First Project - QR Code
# Import QRCode from pyqrcode
import pyqrcode
import png
from pyqrcode import QRCode
  
  
# String which represents the QR code
s = "My First Project In Python"
  
# Generate QR code
url = pyqrcode.create(s)
  
# Create and save the svg file naming "myqr.svg"
url.svg("myqr.svg", scale = 8)
  
# Create and save the png file naming "myqr.png"
url.png('myqr.png', scale = 6)
