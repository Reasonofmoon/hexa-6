<div align="center">

# 💼 hexa-6: IT 서비스 AX 마스터클래스

### *AI로 IT 서비스를 혁신하는 12주 실전 과정*

**제안서작성부터 코드리뷰까지 — 프로젝트 데이터로 직접 검증하는 AX 커리큘럼**

[![Version](https://img.shields.io/badge/version-1.0.0-6366f1?style=for-the-badge)](https://github.com/Reasonofmoon/hexa-6)
[![Colab](https://img.shields.io/badge/Google_Colab-12개_노트북-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://github.com/Reasonofmoon/hexa-6/tree/main/notebooks)
[![Sector](https://img.shields.io/badge/Sector-IT_Services-2563eb?style=for-the-badge&logo=code&logoColor=white)](https://github.com/Reasonofmoon/hexa-6)
[![License](https://img.shields.io/badge/License-MIT-a78bfa?style=for-the-badge)](LICENSE)
[![Scripts](https://img.shields.io/badge/CLI_Scripts-8개-22d3ee?style=for-the-badge&logo=python)](scripts/)

> **"IT 서비스 현장에서 AI 도구를 사용할 수 있는 인력은 전체의 8% 미만이다."**  
> hexa-6은 코딩 경험이 없는 PM·개발자도 Colab 노트북으로  
> 바로 실전 결과를 내도록 설계된 **12주 실무 중심 AX 커리큘럼**입니다.

[📗 커리큘럼 시작](notebooks/) · [🔧 스크립트 도구](scripts/) · [📂 실습 데이터](shared/) · [🐛 이슈](../../issues)

</div>

---

## 🧠 Philosophy — "왜 IT 서비스 AX인가"

기존 IT 서비스 교육의 문제: **프로젝트 데이터가 없이 이론만 있다**.

| 기준 | 기존 AI 교육 | hexa-6 AX 커리큘럼 |
|------|-------------|-------------------|
| 데이터 | 가상의 프로젝트 데이터 | **실제 프로젝트 CSV** (제안, 코드, KPI) |
| 결과물 | 모델 정확도 숫자 | **제안서 + 코드리뷰 + 보안체크** |
| 난이도 | Python 필수 | **Colab 실행만으로 완성** |
| 기간 | 3개월+ 이론 | **Week 1부터 실전 결과** |
| 연결성 | 개별 실습 | **W1→W12 파이프라인으로 연결** |

```mermaid
graph LR
    A[📋 W1-2 제안서작성] --> B[📝 W3-4 기술사양]
    B --> C[📊 W5-6 프로젝트KPI]
    C --> D[📨 W7-8 고객커뮤니케이션]
    D --> E[🔮 W9-10 보안체크]
    E --> F[🎛️ W11-12 통합대시보드]
    
    style A fill:#6366f1,color:#fff
    style F fill:#22d3ee,color:#fff
```

---

## ⚙️ 시스템 레이어

### Layer 1 · Foundation (W1~W4) — AI 기초 도구화
> **Wow**: 10개 제안서 항목을 AI가 **5초 안에** 자동 생성

| 주차 | 노트북 | 핵심 도구 |
|------|--------|-----------|
| W1 | M1_AX_diagnosis.ipynb | Gemini API, 자가진단 |
| W2 | W02_proposal_automation.ipynb | 제안서 자동 생성, 가격 책정 |
| W3 | W03_tech_specification.ipynb | 기술 사양서, 아키텍처 |
| W4 | W04_code_review.ipynb | 코드 리뷰, 자동 검토 |

### Layer 2 · Analytics (W5~W8) — 데이터 기반 의사결정
> **Wow**: 개발 진도·품질·고객만족도를 **클릭 한 번**에 경영진 차트로 변환

| 주차 | 노트북 | 핵심 도구 |
|------|--------|-----------|
| W5 | W05_project_kpi.ipynb | pandas, matplotlib, 프로젝트 KPI |
| W6 | W06_bug_report.ipynb | 버그 리포트, 이슈 추적 |
| W7 | W07_customer_communication.ipynb | 고객 커뮤니케이션, 자동 응답 |
| W8 | W08_deployment_automation.ipynb | 배포 자동화, CI/CD |

### Layer 3 · Intelligence (W9~W12) — 자동화 운영 시스템
> **Wow**: 보안 위혐 시 **자동 분석 → 패치 제안 → 고객 알림** 파이프라인

| 주차 | 노트북 | 핵심 도구 |
|------|--------|-----------|
| W9 | W09_security_check.ipynb | 보안 체크, 취약점 분석 |
| W10 | W10_quality_dashboard.ipynb | 품질 대시보드, 자동 모니터링 |
| W11 | W11_it_dashboard.ipynb | 종합 IT 대시보드 |
| W12 | W12_integrated_operation.ipynb | 통합 운영 시스템 발표 |

---

## 🎯 수준별 활용 가이드

### 🟢 Starter — "5분 안에 첫 결과"
1. [W2 노트북](https://colab.research.google.com/github.com/Reasonofmoon/hexa-6/blob/main/notebooks/W02_proposal_automation.ipynb) 클릭 → Colab에서 열기
2. `PROJECT_INFO`에 프로젝트명·규모만 입력 (`✏️` 표시 찾기)
3. `Shift+Enter`로 위에서 아래로 실행
4. 제안서 초안 + 기술 사양 자동 다운로드

> ⚠️ API 키 발급: [Google AI Studio](https://aistudio.google.com/apikey) → GEMINI_API_KEY

### 🔵 Professional — "내 프로젝트 데이터로 실전 분석"
1. `shared/it_projects_sample.csv` 구조 확인
2. 내 프로젝트 데이터를 같은 형식으로 준비
3. W5~W6 노트북에서 CSV 업로드 → KPI·버그 현황 자동 분석
4. W8 노트북에서 배포 파이프라인 연결 → 자동 배포

```bash
# CLI 스크립트 직접 사용
python scripts/proposal_generator.py --input shared/it_projects_sample.csv
python scripts/project_kpi_analyzer.py --input data.csv --output results.csv
python scripts/code_reviewer.py --input code/ --format [FORMAT]
```

### 🟣 Enterprise — "팀 표준화 & 파이프라인"
1. `scripts/M9_demo_runner.py` 실행 → 전체 파이프라인 원클릭 시연
2. GitHub Actions로 매일 자동 보안 스캔 스케줄링
3. W11~W12를 내부 대시보드로 배포 (Flask/Streamlit)
4. hexa-1, hexa-4와 연계해서 업종 간 벤치마킹

---

## 📂 디렉토리 구조

```
hexa-6/
├── notebooks/          ← 12주 Colab 노트북 (W01~W12)
│   ├── W02_proposal_automation.ipynb     # 제안서 자동 생성기
│   ├── W03_tech_specification.ipynb      # 기술 사양서
│   ├── W04_code_review.ipynb            # 코드 리뷰
│   ├── W05_project_kpi.ipynb            # 프로젝트 KPI 분석
│   ├── W06_bug_report.ipynb             # 버그 리포트
│   ├── W07_customer_communication.ipynb   # 고객 커뮤니케이션
│   ├── W08_deployment_automation.ipynb   # 배포 자동화
│   └── W09_security_check.ipynb         # 보안 체크
├── scripts/            ← CLI 실행 가능 Python 스크립트
│   ├── proposal_generator.py             # 제안서 생성기
│   ├── tech_spec_generator.py           # 기술 사양 생성기
│   ├── code_reviewer.py                # 코드 리뷰 자동화
│   ├── project_kpi_analyzer.py         # 프로젝트 KPI 분석기
│   ├── bug_tracker.py                  # 버그 추적 자동화
│   ├── customer_communicator.py        # 고객 커뮤니케이션
│   ├── deployment_automator.py         # 배포 자동화
│   └── M9_demo_runner.py              # 원클릭 데모 런처
├── shared/             ← 실습 데이터
│   ├── it_projects_sample.csv          # IT 프로젝트 샘플
│   └── code_repository_sample.csv     # 코드 저장소 샘플
└── labs/               ← 실습 가이드 (M2~M7)
    ├── M2-proposal/README.md
    ├── M3-techspec/README.md
    ├── M4-codereview/README.md
    └── M7-it/README.md
```

---

## 🔧 확장 가이드

| 우선순위 | 커스터마이징 | 난이도 | 영향 범위 |
|----------|--------------|--------|-----------|
| **1st** | `PROJECT_INFO` 딕셔너리 수정 | ⭐ | 프로젝트명·규모·기간 |
| **2nd** | 샘플 CSV를 실제 데이터로 교체 | ⭐⭐ | 분석 결과 전체 |
| **3rd** | 배포 파이프라인 연결 | ⭐⭐ | 자동화 운영 |
| **4th** | 보안 스캔 API 인증 설정 | ⭐⭐⭐ | 보안 자동화 |
| **5th** | W11~W12 대시보드 서버 배포 | ⭐⭐⭐ | 팀 공유 시스템 |

---

## 🚀 빠른 시작

```bash
# 1. 레포 클론
git clone https://github.com/Reasonofmoon/hexa-6.git
cd hexa-6

# 2. 환경 설정 (로컬 실행 시)
pip install google-generativeai pandas matplotlib gspread requests

# 3. 데모 실행
python scripts/M9_demo_runner.py

# 4. 제안서 생성 바로 실행
python scripts/proposal_generator.py --input shared/it_projects_sample.csv
```

또는 **Colab에서 바로 실행** (설치 불필요):  
[![W2 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/Reasonofmoon/hexa-6/blob/main/notebooks/W02_proposal_automation.ipynb)
[![W6 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/Reasonofmoon/hexa-6/blob/main/notebooks/W06_bug_report.ipynb)
[![W9 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/Reasonofmoon/hexa-6/blob/main/notebooks/W09_security_check.ipynb)

---

## 🔗 전체 AX 시리즈

| 레포 | 섹터 | 핵심 모듈 |
|------|------|-----------|
| [hexa-1](https://github.com/Reasonofmoon/hexa-1) | 🏭 제조업 | OEE, 불량분류, 예지보전 |
| [hexa-2](https://github.com/Reasonofmoon/hexa-2) | 🍽️ F&B | 리뷰분석, 메뉴카피, 재고예측 |
| [hexa-3](https://github.com/Reasonofmoon/hexa-3) | 🛒 소매/유통 | 상품카피, CRM, SEO |
| [hexa-4](https://github.com/Reasonofmoon/hexa-4) | 📚 교육 | 교안자동화, 성적분석, 챗봇 |
| [hexa-5](https://github.com/Reasonofmoon/hexa-5) | 🏗️ 건설 | 계약서분석, 공정관리 |
| **hexa-6** (현재) | 💼 IT/서비스 | 제안서, 코드리뷰, KPI |

---

## 🌐 다국어 지원

| 항목 | 현황 |
|------|------|
| 노트북 UI | 한국어 |
| 스크립트 출력 | 한국어 (컬럼 자동감지: 한/영) |
| 샘플 데이터 | 한국어 컬럼명 |
| README | 한국어 / English (예정) |

---

*AX Consulting Curriculum © 2026 | Powered by Google Gemini*