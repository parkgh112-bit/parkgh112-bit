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

## 프로젝트

| 프로젝트 | 한 줄 소개 | 스택 |
|:--|:--|:--|
| **AIOps 장애 진단·조치**<br><sub>AICloudWave Team4 · 팀 · 레포 비공개</sub> | Step Functions 기반 에이전트 파이프라인을 설계한 AIOps 전반 설계 담당 | `Step Functions` `Bedrock AgentCore` `Bedrock KB` |
| **[skin_tone_analysis](https://github.com/parkgh112-bit/skin_tone_analysis)**<br><sub>캡스톤</sub> | 얼굴 이미지로 MST 피부톤을 분류하고 전문 장비 데이터와 합쳐 맞춤 추천 제공 | `Next.js` `Flask` `MediaPipe` `LightGBM` |
| **[CanonProject_real](https://github.com/parkgh112-bit/CanonProject_real)** | YOLO로 부품을 찾고 CNN으로 합격/불합격을 판정하는 이미지 검수 도구 | `YOLO` `CNN` `FastAPI` `Next.js` |
| **[tire-hole-detection-project](https://github.com/parkgh112-bit/tire-hole-detection-project)** | SAHI와 CLAHE로 소형 객체 검출 F1을 개선한 타이어 몰드 벤트 홀 검출 | `YOLOv8` `SAHI` `OpenCV` |
| **[audio-preprocessing-pipeline](https://github.com/parkgh112-bit/audio-preprocessing-pipeline)** | 코골이 감지용 전처리·MFCC 추출 담당, 최종 모델 정확도 95.6% / F1 90.6% | `Librosa` `NumPy` `Pandas` |

<details>
<summary><b>AIOps 장애 진단·조치 · 설계 상세 보기</b></summary>

<br>

EKS 위 주문/재고 MSA에 장애를 주입하고, AI 에이전트가 모니터링 → 진단 → 조치까지 하는지 검증한 프로젝트입니다. AIOps 전반의 설계를 맡았습니다.

- **파이프라인**: Step Functions로 에이전트 파이프라인 전체를 설계
- **RAG**: 구성에 쓸 AWS 서비스를 선정 (런북 검색은 Bedrock Knowledge Base)
- **모델**: 에이전트별 사용 모델을 선정
- **도구 권한**: 에이전트별 도구(tool) 권한을 할당하는 방식을 설계
- **예외 처리**: 실패 상황별 예외 처리를 설계
- **배포**: 모니터링/진단/조치 에이전트와 Loki·Prometheus MCP 서버를 AgentCore로 배포
- **인프라**: Terraform으로 구성 (AI 코딩 도구 활용)

</details>

<br>

## 다루는 영역

- **AI 에이전트 파이프라인 설계**: Step Functions, Bedrock AgentCore, RAG
- **컴퓨터 비전**: 객체 검출·분류 모델 학습과 서비스 적용
- **오디오 데이터**: 특징 추출과 분류 모델
- **AWS 기반 서비스 구성**

## 작업 방식

Claude Code 등 AI 코딩 도구로 구현하고, 설계와 검증에 집중합니다.
