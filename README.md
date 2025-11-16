
Colab Test : ImageConvertForLCD.ipynb

Parameter Settings</br>
IMAGE_FOLDER : image 파일들이 포함된 경로 설정</br>
BASE_ADDR : External Memory에 저장될 메모리 시작주소 설정</br>
WIDTH : LCD에 표시할 이미지 Width</br>
HEIGHT : LCD에 표시할 이미지 Height</br>

Examples</br>
STM32N6-DK 보드는 LCD 크기가 800*480</br>
예제에서는 원본 이미지를 미리설정된 WIDTH, HEIGHT값을 참고하여 Resizing</br>
예제에서는 Resizing 완료 이미지를 RGB888로 변경</br>
폴더내에서 검색된 모든 이미지를 .bin 으로 저장 ( 해당 파일을 External Flash에 저장, 저장주소는 BASE_ADDR )</br>
추가로 생성된 .h 헤더파일을 프로젝트에 추가하여 이미지를 불러옴</br>


