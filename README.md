# Real-time-collision-prediction

---
## 1. 배경 & 목적
- 주관 : 전공수업 Deep Learning(DL)
- 목적 : 딥러닝을 활용한 인공지능 연구 제안 기획 및 발표
- 프로젝트 주제 : 객체 탐지와 경로 예측을 통한 실시간 충돌 예측 모델
---

## 2. 프로젝트 진행 순서
1. 선행연구 조사 발표(개인)
2. 최종 발표(팀)

---
## 3. 담당 역할
- Team Leader
- 아이디어 기획
- 선행연구 조사
- 방법론 개발
- 모델 파이프라인 구축
---
## 4. 선행연구 조사 발표(개인)
#### 객체 탐지 분야 조사 후 선정 논문 발표
- **DETR** : End to End Object De tection with Transformers (Facebook AI, 2020)
- **RT-DERT** : DETRs Beat YOLOs on Real time Object Detection (Baidu Inc., 2023)

---
## 5. 최종 발표(팀)
- **주제 선정 배경(연구 동기)**   
산업재해 발생유형 중 부딪힘, 교통사고 약 25%  
예기치 못한 사고를 미연에 방지 , 예방하기 위해 산업 현장 내 객체 간의 충돌 예측 모델 고안  
현장 CCTV 를 통해 실시간 충돌 예측 및 경고 시스템 구축 -> 충돌로 인한 산업재해 발생률 감소 기대

- **기존 충돌 예측 연구 한계점**
  1) 하나의 기준으로 충돌 판단
  2) 객체와 객체 사이의 거리가 멀어 bbox가 겹치지 않는 경우충돌을 예측 할 수 없다는 한계 존재
  3) 작업 차량과 차량 탑승자를 충돌하는 경우로 오판단하는 경우 발생 (IoU의 값이 1에 근사하기 때문)

- **선행 연구 조사**  
객체 탐지 모델, 경로 예측 모델

- **제안 방법론 파이프라인**
  1) Multi-Object Detection & Tracking
  2) Distance Calculation & Predict Trajectory
  3) Collision Prediction & Output

- **실험 시나리오 설계**


---
# 7. 자료
- 발표자료  
  [선행연구 조사 발표.pdf](https://drive.google.com/file/d/1yVpEJaxesETHPn9F5NeQw57UR9uE3CxA/view?usp=drive_link)  
  [최종 발표.pdf](https://drive.google.com/file/d/11KB0dwEv6wM7rpzWCvbeLyHe5vhpmXfd/view?usp=drive_link)
