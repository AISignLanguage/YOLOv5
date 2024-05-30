## Yolov5
https://github.com/ultralytics/yolov5

https://docs.ultralytics.com/ko/yolov5/

YOLOv5 모델은 기존 yolo 모델에 비해 더 뛰어난 물체 감지 성능과 개발에 더 효율적으로 이용할 수 있다. 
추론, 검증, 훈련, 내보내기 등 다양한 기능을 지원한다.

## Model

Ultralytics의 YOLOv5 github를 clone하여, yolov5s.pt를 이용하였다.
13개의 동작 당 30개의 이미지 데이터셋을 직접 수집하였고, 직접 390장을 라벨링하였다.
colab의 gpu 환경에서 yolov5s.pt, yolov5m.pt, yolov5l.pt, yolov5x.pt 중 어플리케이션의 실시간적인 특성과 경량화를 고려하여 가장 가벼운 yolov5s.pt를 통해 epoch를 200번 실행하였다.
도출된 best.pt를 통해 Precision : 0.992, Recall : 0.999, mAP50 : 0.995, mAP50-95 : 0.896로 우수한 성능의 모델을 얻었다.
