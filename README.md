# FindingLungsInCTData

참고
: https://www.youtube.com/watch?v=z8lK69BQ0VE (빵형의 개발도상국) 

사용한 모델
: Convolutional Encoder-Decoder (Covolutional Neural Network로 이루어진 Encoder와 Decoder) 
Encoder = 차원 축소를 통해 핵심 요소만 뽑아낸다. Downsampling(CNN에서는 MaxPooling2D를 사용) 
Decoder = 압축된 정보로부터 차원 확장을 통해 원하는 정보로 복원한다. Upsampling(CNN에서는 UpSampling2D를 사용) 

