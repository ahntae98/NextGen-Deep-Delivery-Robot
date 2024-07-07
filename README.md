# 프로젝트명
> 국민대학교 전자공학부 지능형 무선 시스템 연구실

객체 인식을 활용한 자율주행 배달로봇 프로젝트
![](../header.png)

## 사용 OS
Linux Ubuntu 20.04

## 사용 Tool
ROS1

## 사용한 센서
1. D435i - 객체 탐지용 카메라

![D435i](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/fd3157cc-7e4b-49ab-8544-c28555216b07)

3. T265i - 로봇의 위치 추정

![t265](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/7ec0b950-8551-4c1f-8547-7da42c07e495)

5. RPLidar S2 - 2D 맵 생성 및 장애물 인식

![S2lidar](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/c898979c-6cb4-4d4f-be74-3ed79271a698)

## URDF(TF) 설정

![ㅅㄹ](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/911060c0-ce1d-4d8d-bd23-e1a2a3dc53d7)

각 센서들은 3차원 좌표계에서 각자의 고유 좌표를 가지고 있다. 따라서 하나의 로봇에 묶어 동작하기 위해서는 강제로 이들의 상대 좌표들을 묶어주는 작업이 필요하다

## 2D Map 생성

![맵1](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/955e7fea-ee66-4890-96ba-92fb86bdba87)

turtlebot3_teleop을 실행해 로봇을 조종하며 S2 lidar로 2D Map을 생성한 모습

## 객체 인식

![객체인식](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/6828455f-5ed1-4e09-bd98-e46a1d581206)

로봇에 부착된 카메라 센서(D435i)를 통해 객체(숫자)를 인식하는 모습

## 최종 프레임

![시랏](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/d5cc0ee1-82b3-4251-8917-cf72c83f375e)

## 최종 구현 화면
![KakaoTalk_20240528_174320609_01](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/befbcb33-8ad9-45eb-b942-d2e1207cdb80)
![result_robot](https://github.com/ahntae98/NextGen-Deep-Delivery-Robot/assets/133379277/413dbcb2-fd9f-4f29-811c-110159734d32)


## 작업자

김기현, 안태현, 기운찬, 김동민, 남궁민석

[Github repository](https://github.com/gyun2/Delivery-bot-KMU)

## 기여 방법


<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
