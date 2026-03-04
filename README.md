# 💼 hexa-6: 전문서비스/IT AX 마스터클래스

> "제안서가 3분 만에 완성" — 전문서비스/IT 중소기업을 위한 AI 자동화 실습 과정

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/hexa-6/blob/main/notebooks/M7_PROPOSAL_document_lab.ipynb)

---

## 🎯 이 과정은?

**대상**: IT 서비스, 컨설팅, 소프트웨어 개발, 디지털 에이전시  
**목표**: 제안서 자동 생성·코드 리뷰·기술 문서 3가지 핵심 자동화  
**시간**: 6시간 (강의 3h + 실습 3h)

---

## 🎯 수준별 활용 가이드

### 🟢 Starter — "5분 안에 제안서 초안"
1. `labs/M7-PROPOSAL/README.md` 열기
2. 프롬프트 복사 → ChatGPT/뤼튼에 붙여넣기
3. 프로젝트명·규모·기간만 수정 후 Enter
4. 제안서 즉시 출력 ✅ (코딩 0줄)

### 🔵 Professional — Colab 자동화
```python
# Colab Secret에 저장 (이름: GEMINI_API_KEY)
from google.colab import userdata
api_key = userdata.get('GEMINI_API_KEY')
```
1. Colab 뱃지 클릭 → 노트북 오픈
2. 런타임 → 모두 실행
3. 프로젝트 정보 셀만 수정
4. 제안서 + 코드리뷰 CSV 자동 다운로드

### 🟣 Enterprise — 멀티 에이전트 파이프라인
- OMC `/team 3:executor`로 분석→제안→코드→배포 자동화
- `AGENTS.md` 기반 기술 표준 내재화
- `scripts/agents_config_validator.py` 셀프 검증

---

## ⚙️ 3모듈 커리큘럼

| 모듈 | 제목 | Colab | Labs |
|---|---|---|---|
| M1 | AX 진단 & IT 서비스 벤치마킹 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/M1_AX_diagnosis.ipynb) | [labs/M1](labs/M1-diagnosis/) |
| M7-PROPOSAL | 제안서 생성 & 코드 리뷰 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/M7_PROPOSAL_document_lab.ipynb) | [labs/M7-PROPOSAL](labs/M7-PROPOSAL/) |
| M9 | 자동배포 & 관제 시스템 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/M9_deployment_auto.ipynb) | [labs/M9](labs/M9-deploy/) |

---

## 📂 프로젝트 구조

```
hexa-6/
├── notebooks/
│   ├── M1_AX_diagnosis.ipynb           ← AX 진단 자동화
│   ├── M7_PROPOSAL_document_lab.ipynb   ← 제안서 생성 ★
│   └── M9_deployment_auto.ipynb        ← 자동배포 시스템
├── labs/
│   ├── M1-diagnosis/README.md           ← 진단 프롬프트 모음
│   ├── M7-PROPOSAL/README.md          ← IT 실습 가이드
│   └── M9-deploy/README.md            ← 배포 체크리스트
├── scripts/
│   ├── proposal_generator.py            ← 제안서 생성 (실행 가능)
│   ├── code_review_analyzer.py         ← 코드 리뷰 분석
│   └── agents_config_validator.py      ← AGENTS.md 검증
└── shared/
    └── it_projects_sample.csv          ← 샘플 프로젝트 데이터 (25행)
```

---

## 🌐 hexa 시리즈
- [hexa-1](https://github.com/Reasonofmoon/hexa-1): 🏭 제조업
- [hexa-2](https://github.com/Reasonofmoon/hexa-2): 🍽️ 외식/F&B
- [hexa-3](https://github.com/Reasonofmoon/hexa-3): 🛒 소매/유통
- [hexa-4](https://github.com/Reasonofmoon/hexa-4): 📚 교육/에드테크
- [hexa-5](https://github.com/Reasonofmoon/hexa-5): 🏗️ 건설/부동산
- **hexa-6** (현재): 💼 전문서비스/IT

Made with ❤️ by [Reasonofmoon × Antigravity](https://github.com/Reasonofmoon)  
중소기업 AX 전환을 위한 실전 교육