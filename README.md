# MTCNN-Mosaic

1. https://github.com/ipazc/mtcnn 여기서 git colon 한다.

2. clone한 폴더에 haarcascade_frontalface_alt2.xml 둔다. ('./MTCNN/mtcnn') 폴더
OpenCV의 face recognition은 https://www.youtube.com/watch?v=PmZ29Vta7Vc&t=2827s 를 보고 만들었다.

3. clone한 폴더에 올린 주피터노트북도 같이 둔다. (위와 같은 경로)

4. 이미지 파일은 정사각형으로 얼굴부분만 잘라서 학습시킨다.

5. conf 조절 하면서 얼굴인식 진행한다. 

6. MTCNN에서 나온 좌표값으로 모자이크를 진행한다.
