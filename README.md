#라즈베리 활용 미니 프로젝트

## 보행자 감지 신호등 시스템

## 작품 개요 : 보행자가 감지되었을 때만 도로의 신호등을 제어해 차량의 흐름을 원활히 하는 교통제어 시스

### 작품 제작에 사용한 센서와 엑추에이터
- 버튼 : 시스템 작동 시작
- 초음파 센서 : 보행자 감지
- LED : 신호등 점등

## 완성 작품

### 작품 회로도

### 작품 사진

## 동작 시나리오 및 예시
1. 평소에는 자동차 신호등이 상시 초록불로 켜져 있음
2. 초음파 센서에 보행자가 감지된 상태에서 보행자가 버튼을 누르면, 시스템이 작동해 신호등 불빛이 주황, 빨강 순으로 바뀜.
3. 일정 시간이 지나면, 다시 초록불 상시 점등 상태로 돌아옴. 신호가 바뀌기 전 MQTT로 신호가 바뀌기 전까지 남은 시간을 미리 알려줌.

## 기대 효과 : 불필요한 보행 신호 점등을 없앰으로 교통체증 해소, 시간 절약 등 사회적 비용 감소효과
