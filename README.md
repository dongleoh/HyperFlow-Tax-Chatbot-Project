# 💬 HyperFlow API 기반 RAG 세법 상담 챗봇

> **웹 개발 + AI 연동 프로젝트**  
> 노코드 AI 구축 플랫폼 **HyperFlow API**를 활용하여 **RAG 기반 세법 상담 챗봇 시스템**을 완성한 프로젝트입니다.

---

## 🧠 프로젝트 개요

세법과 같은 전문 지식을 요구하는 상담을 보다 직관적이고 빠르게 제공하기 위해, HyperFlow의 RAG 기반 응답 시스템을 활용하여 사용자에게 관련 정보를 제공합니다.

- **RAG (Retrieval-Augmented Generation)** 기반 AI 응답
- PDF 업로드를 통한 **지식 세그먼트 추출 방식**
- 노코드 플랫폼을 최대한 활용하되, 프론트엔드/백엔드는 코드로 커스터마이징
- **작업 소요 시간**: 약 10시간 (버그 수정 포함)

---

## 🛠️ 기술 스택 및 툴

| 범주         | 기술/도구                      |
|--------------|-------------------------------|
| AI API 연동  | HyperFlow AI (RAG 기반 시스템) |
| UI 디자인    | Figma Design                 |
| 프론트엔드   | React.js, Bolt UI, Cursor AI  |
| 백엔드       | API 연동 via Cursor AI        |
| 배포         | 로컬 환경 및 데모 영상 확인    |

---

## 📌 주요 기능 요약

- 📑 **PDF 기반 문서 업로드** → 세그멘테이션 → RAG 지식 저장소 구성
- 🔌 **HyperFlow API 연동**으로 노코드 환경에서 실시간 응답 구현
- 🎨 **Figma + Bolt** 조합을 통해 인터랙션 가능한 UI 구성
- 🔄 **Cursor AI**를 통한 프론트 ↔ 백엔드 API 연결

---

## 🔍 시스템 아키텍처 흐름

### 1. 하이퍼플로우 플로우그래프

> 시각적 플로우 구성만으로도 내부 RAG 정보 참조를 자동화  
> <img width="1791" height="930" alt="image" src="https://github.com/user-attachments/assets/1b2ed13d-a1e3-49ae-a4d8-7b2e4473b870" />


---

### 2. PDF 업로드 기반 응답 시스템

- 크롤링 없이 사용자가 직접 세법 PDF 입력
- 문서 세분화를 통한 지식 데이터 구성
- 이후 GPT 모델이 이를 참조해 응답

---

### 3. UI 및 연동 과정

#### 🎨 Figma를 통한 기본 디자인 프레임

> <img width="1792" height="922" alt="image" src="https://github.com/user-attachments/assets/f5aec2eb-1979-4132-b23f-71f330e158ca" />


#### ⚙️ Bolt를 활용한 UI 상호작용 구현

> <img width="1789" height="921" alt="image" src="https://github.com/user-attachments/assets/9d7736ec-215b-4f38-aa53-9c049139be78" />


#### 🧩 Cursor AI를 활용한 API 연결

> <img width="1484" height="919" alt="image" src="https://github.com/user-attachments/assets/7e4cf1ca-2847-43fd-934d-e8f48cf6470d" />


---

## 🎬 데모 영상 (코엑스 런칭 컨퍼런스에서 데모 시연)

> 완성된 챗봇 시스템의 실제 동작 예시와 시연 영상은 아래 링크에서 확인하실 수 있습니다.

https://youtu.be/vrVjv79KWOw?si=oFLwUVQJ8sVMMBKA

---

## 📁 프로젝트 구조 예시


📦 taxy
├── 📁 node_modules/           # 설치된 의존성 라이브러리
├── 📁 public/                 # 정적 파일 (예: favicon, 공개 assets 등)
├── 📁 src/                    # 주요 소스 코드 디렉터리
│
├── hyperflow.js              # Hyperflow API 연동 스크립트
├── index.html                # 앱 진입 HTML
├── package.json              # 프로젝트 메타 정보 및 의존성 정의
├── package-lock.json         # 고정된 의존성 버전 정보
├── README.md                 # 프로젝트 설명 문서
│
├── tailwind.config.js        # TailwindCSS 구성 파일
├── tailwind.css              # TailwindCSS 커스터마이징 스타일
│
├── tsconfig.json             # TypeScript 전체 설정
├── tsconfig.app.json         # 애플리케이션 빌드용 TS 설정
├── tsconfig.node.json        # Node 실행용 TS 설정
├── vite.config.ts            # Vite 번들러 구성 파일


---

## 🔮 확장 가능성

- 크롤링 기능 추가 → 외부 세법 사이트 자동 동기화
- 다국어 세법 문서 대응 (국제 사용자 확장)
- GPT 파인튜닝 연동 (HyperFlow 외부 커스터마이징)

---

> ⓒ 2025 | RAG 기반 세법 상담 챗봇 | HyperFlow x Cursor x Bolt 프로젝트


