# Rotation_degree_prediction
camera_gripper_robot이 HUSKYLENS을 활용해 주변환경을 학습해서 목표지점을 찾을 수 있다는 것을 확인했다.

HUSKYLENS는 학습 데이터만 넣어주면 자동으로 학습이 진행된다는 편리함이 있지만 많은 양의 학습 데이터를 모으기 불편하고 학습을 할 수 있는 방법이 제한적이라는 단점 때문에 예측의 정확도가 충분하지 않았다.

그래서 HUSKYLENS보다 정확도가 높은 인공신경망을 만들고 이 인공신경망을 활용해 로봇이 회전한 각도를 예측하고자 한다.
