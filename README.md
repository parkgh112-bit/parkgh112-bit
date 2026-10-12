## parkgh112-bit

컴퓨터 비전과 오디오 데이터로 모델을 만들고, 그 모델이 돌아가는 서비스까지 붙여 보는 프로젝트를 해 왔습니다.
요즘은 AWS EKS 위의 주문/재고 서비스에 장애를 일으키고, AI 에이전트가 원인을 찾아 조치하는지 검증하는 팀 프로젝트를 하고 있습니다.

### 프로젝트

**AICloudWave Team4 · AIOps 장애 진단/조치** (팀, 비공개)
EKS 위 MSA 서비스에 장애를 주입하고, 에이전트가 모니터링 → 진단 → 조치까지 하는지 확인합니다.
에이전트/MCP 서버 코드(dbnj-aiops)와 Terraform 인프라(dbnj-infra)를 작업했습니다.
Python, Terraform, EKS, Aurora, SQS, Bedrock AgentCore, Prometheus, Loki

**[skin_tone_analysis](https://github.com/parkgh112-bit/skin_tone_analysis)** · 캡스톤
얼굴 이미지에서 MST 스케일 피부톤을 분류하고, 전문 장비(Mark-Vu) 측정값과 합쳐 리포트와 맞춤 추천을 보여주는 웹 서비스입니다.
Next.js, Flask, MediaPipe, LightGBM, Supabase, Gemini API

**[CanonProject_real](https://github.com/parkgh112-bit/CanonProject_real)**
제품 이미지에서 부품을 YOLO로 찾고 CNN으로 합격/불합격을 판정하는 검수 도구입니다. 실시간 카메라 분석과 일괄 분석, CSV 내보내기를 지원합니다.
YOLO, CNN, FastAPI, Next.js

**[tire-hole-detection-project](https://github.com/parkgh112-bit/tire-hole-detection-project)**
타이어 몰드의 미세한 벤트 홀 검출입니다. 작은 객체가 잘 안 잡혀서 SAHI 슬라이싱 추론과 CLAHE 전처리로 F1을 끌어올리는 데 집중했습니다.
YOLOv8, SAHI, OpenCV, Albumentations

**[audio-preprocessing-pipeline](https://github.com/parkgh112-bit/audio-preprocessing-pipeline)**
코골이 감지 프로젝트에서 데이터 전처리와 특징 추출을 맡았습니다. 1초 단위로 잘라 데이터를 늘리고 39차원 MFCC를 뽑았으며, 최종 모델은 정확도 95.6%, F1 90.6%가 나왔습니다.
Python, Librosa, NumPy, Pandas

### 사용하는 도구

Python, TypeScript · FastAPI, Flask, Next.js · PostgreSQL · Docker, Terraform, AWS
