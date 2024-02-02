# Stegg
LSB steganography is a technique used to hide information within an image, audio, or other digital media by altering the least significant bits of the pixels or samples. In digital data, each byte consists of 8 bits, and the least significant bit is the rightmost bit.

****Note: This tool only works with png images****

____  _                     _           
/ ___|| |_ ___  __ _  __ _  | |__  _   _ 
\___ \| __/ _ \/ _` |/ _` | | '_ \| | | |
 ___) | ||  __/ (_| | (_| | | |_) | |_| |
|____/ \__\___|\__, |\__, | |_.__/ \__, |
               |___/ |___/         |___/ 
 _     ___  ____ _____ ____   _____   __
| |   / _ \/ ___|_   _| __ ) / _ \ \ / /
| |  | | | \___ \ | | |  _ \| | | \ V / 
| |__| |_| |___) || | | |_) | |_| || |  
|_____\___/|____/ |_| |____/ \___/ |_|  
                                        
usage: stegg [-h] [-e E] [-f F] [-x] [-p [P]]

Image Steganography [+] Use .png files only

options:
  -h, --help  show this help message and exit
  -e E        To embed a message in the image
  -f F        To pass .png (Image) file
  -x          To extract the message from the image.
  -p [P]      To put in a password.
                                                                                
Installation:
git clone https://github.com/div3107/Stegg

Usage:
python stegg -h 
 ____  _                     _           
/ ___|| |_ ___  __ _  __ _  | |__  _   _ 
\___ \| __/ _ \/ _` |/ _` | | '_ \| | | |
 ___) | ||  __/ (_| | (_| | | |_) | |_| |
|____/ \__\___|\__, |\__, | |_.__/ \__, |
               |___/ |___/         |___/ 
 _     ___  ____ _____ ____   _____   __
| |   / _ \/ ___|_   _| __ ) / _ \ \ / /
| |  | | | \___ \ | | |  _ \| | | \ V / 
| |__| |_| |___) || | | |_) | |_| || |  
|_____\___/|____/ |_| |____/ \___/ |_|  
                                        

**usage**: stegg [-h] [-e E] [-f F] [-x] [-p [P]]

Image Steganography [+] Use .png files only

options:
  -h, --help  show this help message and exit
  -e E        To embed a message in the image
  -f F        To pass .png (Image) file
  -x          To extract the message from the image.
  -p [P]      To put in a password.


**python stegg -e hello -f example.png** 
