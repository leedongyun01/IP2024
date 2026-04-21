# IP2024: Image Processing & Computer Vision 실습

OpenCV와 Python을 활용하여 영상 처리의 기초부터 고수준 알고리즘(추적, 배경 분리, 포즈 추정)까지 단계별로 구현.

## 프로젝트 구조

### 1. OpenCV 핵심 기능 실습 (`Chap` 시리즈)
* **기초 및 GUI (`Chap 1.2`)**: 비디오 스트리밍, 기하학적 도형 렌더링, 마우스 콜백 함수 및 트랙바를 활용한 사용자 인터랙션 구현.
* **영상 연산 (`Chap 1.3`)**: 이미지 합성(`addWeighted`), ROI(관심 영역) 추출, 비트 연산 기반 마스킹 및 성능 측정(`TickCount`).
* **색 공간 및 변환 (`Chap 1.4`)**: BGR/HSV/Gray 변환, 특정 색상 영역 검출(`inRange`), 보간법을 이용한 이미지 리사이징.
* **고급 분석 (`Chap 1.6~1.7`)**:
    * **Optical Flow**: Lucas-Kanade 알고리즘 및 Dense Optical Flow 기반 객체 이동 분석.
    * **Background Subtraction**: MOG2, GMG 알고리즘을 이용한 동적 배경 분리.
    * **Pose Estimation**: 카메라 캘리브레이션을 통한 2D 이미지 내 3D 좌표계 및 입체 도형 투영.

### 2. 종합 과제 (`Homework`)
* **HW 1**: 마우스 드래그를 이용한 실시간 ROI 선택 및 특정 채널 값 강조.
[hw1link]
[hw1link]: https://youtu.be/gmGGQnETNt0
<img width="60%" src="https://github.com/user-attachments/assets/2fcf5fa8-3c03-4a80-a122-222aa2cf4e7e"/>
* **HW 2**: 트랙바를 활용한 동적 HSV 필터링 및 실시간 특정 객체 검출.
* [hw2link]
* **HW 3**: `Perspective Transform`을 활용한 왜곡된 평면 이미지의 정면 보정 및 원근 변환.
* [hw3link]
* **HW 4**: 비디오 데이터 분석 및 모션 트래킹 알고리즘 구현.
* [hw4link]

* [hw2link]: https://youtu.be/mRtuVvzEcHU
* <img width="60%" src="https://github.com/user-attachments/assets/d2de4f90-6934-4748-a8ab-7bda443336eb"/>

### 3. 파이썬 기초 튜토리얼 (`Tutorial`)
* 영상 처리 알고리즘 구현에 필요한 핵심 문법 정리.
* 자료 구조(List, Tuple, Dict), 제어문, 리스트 컴프리헨션, 람다 함수 등.

## 🛠 기술 스택
* **Language**: Python 3.x
* **Library**: OpenCV (`cv2`), NumPy, Matplotlib, Glob
* **Environment**: Jupyter Notebook (`.ipynb`)
