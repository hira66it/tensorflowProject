# tensorflowProject
>stuy for Tensorflow

1. 나만의 데이터로 v3 모델 학습시키기  
[블로그 : flower](https://meisteruser.net/devflow/2279)  


>환경설정
이렇게 데이터셋을 준비한 다음에 아래의 명령어로 아래에 첨부된 코드를 실행해서 Inception v3 모델의 retraining을 시작한다.-retraining에 사용할 이미지들이 있는 root directory 경로를 flag로 전달해주어야만 한다.  
* Reference : [solaris](http://solarisailab.com/archives/1422)

1. **Mac**  
python inceptionv3_retrain.py --image_dir ~/cat_photos
2. **Windows**  
python inceptionv3_retrain.py --image_dir C:\\cat_photos 

[학습시키기](https://gist.github.com/hira66it/6be1ba161319cd92c705f26f6b873330)
[실행하기](https://gist.github.com/hira66it/0dc965150d9a420789abeaba9504dc73)
