<h1 align="center">parkgh112-bit</h1>

<p align="center">
  모델을 만들고, 그 모델이 돌아가는 서비스까지 붙여 보는 개발자입니다.
</p>

<p align="center">
  <img alt="Computer Vision" src="https://img.shields.io/badge/Computer%20Vision-0f172a?style=flat-square">
  <img alt="Audio Processing" src="https://img.shields.io/badge/Audio%20Processing-0f172a?style=flat-square">
  <img alt="Cloud / AIOps" src="https://img.shields.io/badge/Cloud%20%2F%20AIOps-0f172a?style=flat-square">
</p>

<br>

## 지금 하는 일

AWS EKS 위의 주문/재고 서비스에 장애를 일으키고, AI 에이전트가 원인을 찾아 조치하는지 검증하는 팀 프로젝트(AICloudWave Team4)를 하고 있습니다.
에이전트/MCP 서버 코드(`dbnj-aiops`)와 Terraform 인프라(`dbnj-infra`)를 작업했습니다. 두 레포는 비공개입니다.

<br>

## 프로젝트

| 프로젝트 | 내용 | 스택 |
|:--|:--|:--|
| **[skin_tone_analysis](https://github.com/parkgh112-bit/skin_tone_analysis)**<br><sub>캡스톤</sub> | 얼굴 이미지에서 MST 스케일 피부톤을 분류하고, 전문 장비(Mark-Vu) 측정값과 합쳐 리포트와 맞춤 추천을 보여주는 웹 서비스 | `Next.js` `Flask` `MediaPipe` `LightGBM` `Gemini API` |
| **[CanonProject_real](https://github.com/parkgh112-bit/CanonProject_real)** | 제품 이미지에서 부품을 YOLO로 찾고 CNN으로 합격/불합격을 판정하는 검수 도구. 실시간 카메라 분석, 일괄 분석, CSV 내보내기 지원 | `YOLO` `CNN` `FastAPI` `Next.js` |
| **[tire-hole-detection-project](https://github.com/parkgh112-bit/tire-hole-detection-project)** | 타이어 몰드의 미세한 벤트 홀 검출. 작은 객체가 잘 안 잡혀서 SAHI 슬라이싱 추론과 CLAHE 전처리로 F1 개선 | `YOLOv8` `SAHI` `OpenCV` |
| **[audio-preprocessing-pipeline](https://github.com/parkgh112-bit/audio-preprocessing-pipeline)** | 코골이 감지 프로젝트의 전처리와 특징 추출 담당. 1초 단위 슬라이싱으로 데이터 증강, 39차원 MFCC 추출. 최종 모델 정확도 95.6%, F1 90.6% | `Librosa` `NumPy` `Pandas` |

<br>

## 기술 스택

<p>
  <img alt="Python, TypeScript, Next.js, Flask, FastAPI, OpenCV, Docker, Terraform, AWS, Kubernetes, PostgreSQL, Prometheus, Grafana" src="https://skillicons.dev/icons?i=py,ts,nextjs,flask,fastapi,opencv,docker,terraform,aws,kubernetes,postgres,prometheus,grafana&perline=13">
</p>
