# siamese_test_keras

다음 세가지에 대해 진행

+ face_data
훈련 결과가 명확하지 않음

+ mnist
단순한 Siamese NN인데 정확도가 매우 높음

+ face_data(vgg_baseline)
같은 pair에 대해서는 정확도가 높음 그렇지만 다른 같은 class인데 다른 사진인 경우 조금 낮음
그렇지만 같은 class의 경우 [0.5,0.9] 다른 class에서 [0.9,) 로 결과값이 반환되므로 꽤 유의미한 결과가 나온듯 보임.
