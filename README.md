# FindingLungsInCTData

### Project 내용
: 폐 CT에서 폐의 영역만 분리하는 Segmentation. 인공지능이 폐결핵, 폐암, 폐렴을 진단하기 위해서는 우선 폐영역을 정확히 분리해낼 필요가 있음. 

### Reference
: https://www.youtube.com/watch?v=z8lK69BQ0VE 

: https://tykimos.github.io/2017/01/27/CNN_Layer_Talk/ (컨볼루션 신경망 레이어 이야기) 

### Model
: Convolutional Encoder-Decoder (Covolutional Neural Network로 이루어진 Encoder와 Decoder) 

Encoder = 차원 축소를 통해 핵심 요소만 뽑아낸다. Downsampling(CNN에서는 MaxPooling2D를 사용) 

Decoder = 압축된 정보로부터 차원 확장을 통해 원하는 정보로 복원한다. Upsampling(CNN에서는 UpSampling2D를 사용) 

---

### Output 예시

![image](https://user-images.githubusercontent.com/87505072/130883793-1b2239e7-5b96-4bf0-b90a-143590564fd5.png)

왼쪽 : 원본 이미지

중간 : 주어진 결과 이미지 

오른쪽 : CNN 결과
