# tizen-door-control
Tizen IoT Application, door camera, door bell and door lock control

## 팀명 및 팀원
* 셈틀 / 이동구, 김동균, 신재현, 이창한, 오윤혁
* 이동구 기획/ 김동균 디자인/ 신재현 설계/ 이창한 개발/ 오윤혁 디버깅

## 프로젝트 제목
* 1인 가구를 위한 현관 카메라, 초인종, 도어락 통합 시스템

## 프로젝트 배경 혹은 목적
* 늘어나는 1인 가구 수에 맞추어 보안 강화 및 편의성 증가를 위해서 스마트폰을 활용한 간단한 인터폰 시스템을 구상하였습니다. 
 방문자가 초인종을 누르면 사진이 찍히게 되고 이 사진은 아마존 웹서비스 클라우드로 전송되어 스마트폰에 설치된 어플리케이션을 
 통해 확인을 할 수 있습니다. 또한, 스마트폰을 사용함으로써 어플리케이션을 통한 간단한 조작이 가능하여 손쉬운 사용을 통해 
 편리성을 확보하였습니다.
 
 
 
## 파일 리스트

https://github.com/OHYOONHYUK/semtle_
 안드로이드 파일은 수정 부분 스크립트로 업로드했습니다.

 
## 코드 기여자

* inc/aws_iot_config.h 재현 동구 동균
 src/resource/resource_switch.c SWITCH_IN 창한
 src/resource/resource_servo_motor.c SARTIK_PWM_PIN 윤혁
 


 
##보드
RPI3+ : 센서 연동 및 클라우드 전송

##구현사항
GPIO / PWM 사용
AWS 클라우드
카메라 사용
이미지 분석 사용하지 않음
HTTP Server 사용하지 않음

https://github.com/OHYOONHYUK/semtle_