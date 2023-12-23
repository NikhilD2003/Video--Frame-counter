# Video--Frame-counter
# Code
import cv2

cap=cv2.VideoCapture("C:/Users/asus/Desktop/Venice_10.mp4")

i=0
while(cap.isOpened()):
flag,frame=cap.read()
if flag==False:
break
path='D:/frames/number of frames'+str(i)+'.jpg'
cv2.imwrite(path,frame)
i+=1

cap.release()
cv2.destroyAllWindows()
# Video
https://github.com/NikhilD2003/Video--Frame-counter/assets/150776453/7fe17841-6e59-43d5-9539-3161d9cab827
# Frames
