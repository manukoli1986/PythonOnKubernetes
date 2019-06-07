#import OPencv
numpy- module which handles metrics
cv2 - module to open cv
#read the image
img = cv2.imread('homer-simpson.png') - this will store image in img
#do the processing
#show image
cv2.imshow('image',img) - image window
#close n exit
cv2.waitKey(0)
cv2.destroyAllWindows()

====== code

00:01:24 root@:/opt/flask# ls
__pycache__  app.py  requirement.txt  static  templates
