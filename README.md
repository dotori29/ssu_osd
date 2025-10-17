# ssu_osd
## Focusguardian: AI 집중력 모니터링 및 관리 시스템
"**AI가 당신의 집중력을 지켜드립니다!**"<br>
웹캠을 통해 사용자의 학습을 감지하여 집중력을 유지하고 효율적인 학습 습관을 형성하도록 돕는 AI 기반 집중 관리 서비스입니다.

### 프로젝트 개요
FocusGuardian은 사용자의 **웹캠 영상에서 집중 여부를 감지**하고,
집중이 흐트러지면 즉시 **알림(Popup)** 으로 경고 메시지를 띄워주는 시스템입니다.
또한, **뽀모도로 학습법**을 기반으로 한 시간 관리 기능을 통해
사용자의 학습 효율과 몰입도를 향상시키는 것을 목표로 합니다.

### 프로젝트 목표
- 실시간 집중력 감지 및 경고 알림 제공
- 뽀모도로 방식 학습 타이머 내장
- 집중 기록 데이터 기반 시각화 대시보드 제공
- 장기적으로 AI 피드백 및 집중 패턴 분석 리포트 자동 생성

### 사용 기술
| 구분               | 기술 스택                                           |
| ----------------- | ------------------------------------------------ |
| **Frontend**      | React                                            |
| **Backend**       | Flask / FastAPI                                  |
| **AI 모델**        | MediaPipe (FaceMesh, Iris), OpenCV, Hugging Face |
| **Database**      | SQLite 또는 Firebase                              |
| **Visualization** | Chart.js, Recharts                               |
| **AI Feedback**   | LangChain + Gemini API                           |

### 주요 기능
- 실시간 집중 감지 + 팝업형 알림
- 학습 집중 데이터 시각화(경고 알림 횟수, 평균 집중 시간 등)
- AI 피드백 제공(적절한 학습 시간과 루틴 추천)
- 뽀모도로 타이머

### 참고 문헌
1. [*Real-Time Gaze Estimation Using Webcam-Based CNN Models for Human–Computer Interaction.*](https://www.mdpi.com/2073-431X/14/2/57)
2. [*Video-based Real-time Monitoring of Engagement in E-learning.*](https://www.sciencedirect.com/science/article/abs/pii/S0957417425018585)



