# opencv
opencv projects

FACE DETECTION :

start Webcamera <br>
use a face classifier -haarcascade<br><br>
while loop for video(by capturing and showing images continuously)<br>
    read webcamera  <br>
    converting to gray image<br>
    Apply face classifier<br>
    get rectangle points and length <br>
          draw rectangle on original image with those points and length<br>
    finally show image <br>
    apply waitkey()  ESC key to stop recording<br>
         	break loop<br><br>
close/destroy all recording windows<br>
close/release camera <br>
