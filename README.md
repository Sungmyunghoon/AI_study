# AI BOOK

## 1. 환경설정 ( NVIDA + Cuda -> pytorch + pychorm )

NVIDA + Cuda 를 사용할려면 자신이 갖고 있는 GPU의 성능을 알고있어야 함.

## GPU 모델 확인

GPU 모델에 따라 설치해야하는 CUDA와 cuDNN 버전이 다름

cuDNN = "CUDA Deep Neural Network library" => NVIDIA가 개발한 딥러닝 프레임워크에 최적화된 GPU 가속 라이브러리

딥러닝 연산을 가속화하고 GPU 성능을 극대화

GPU확인 방법 = 원도우 키 -> 장치 관리자 -> 디스플레이 어댑터 

![image](https://github.com/Sungmyunghoon/AI_study/assets/112747810/99ff3fee-8e51-4c56-91cd-0b781e449941)

# CUDA Tool Kit 다운로드 ( RTX 3050ti ) 11.6.0

https://developer.nvidia.com/cuda-toolkit-archive

# NVIDIA 그래픽 드라이버 설치

GPU 하드웨어와 운영 체제 간의 통신을 가능하게 하는 역할

CUDA가 GPU를 활용하여 병렬 계산을 수행할 수 있도록 하는 기본적인 요소

https://www.nvidia.co.kr/Download/index.aspx?lang=kr#

명령 프롬포트에 nvidia-smi을 입력하면 확인 가능

# CUDA 버전 확인

https://en.wikipedia.org/wiki/CUDA#GPUs_supported

# pytorch 다운로드

https://pytorch.org/get-started/locally/

# CUDA Toolkit 설치
