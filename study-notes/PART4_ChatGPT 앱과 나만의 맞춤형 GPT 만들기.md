# PART 4. ChatGPT 앱과 나만의 맞춤형 GPT 만들기

> 강환수 교수 | 생성형 AI 시대의 LLM 활용서 | 동양미래대학교

---

## 9. ChatGPT 앱 활용

### ChatGPT 데스크탑 앱이란?
- 브라우저 없이 독립 실행 가능한 네이티브 앱
- `Alt+Tab` 전환으로 멀티태스킹 지원
- 단축키, 다크 모드, 알림 등 Windows 시스템 연동
- 브라우저 대비 메모리 사용 감소 및 안정적 실행

### 설치 방법
- 공식 다운로드: https://openai.com/chatgpt/download/
- Microsoft Store: https://apps.microsoft.com/ → "chatgpt app download" 검색
- `ChatGPT Installer.exe` 실행 후 설치

### 실행 흐름
1. 앱 실행 → 로그인 (이메일 또는 Google)
2. 워크스페이스 선택 (개인 계정 / 학교 조직 계정)
3. 웹 버전과 유사한 UI 화면 진입

---

## 10. GPT 탐색: 나만의 GPT 만들기

### 맞춤형 GPT란?
- 사용자의 목적·스타일에 맞게 GPT의 성격, 행동, 지침을 자유롭게 설정
- **프로그래밍 지식 불필요** — 누구나 쉽게 생성 가능
- 활용 예시: 개인 비서, 학습 튜터, 고객 상담 챗봇
- **ChatGPT Pro(유료)** 사용자 대상 기능

### GPT 만들기 접근 방법
| 방법 | 경로 |
|------|------|
| 프로필 아이콘 클릭 | 우측 상단 → 내 GPT → GPT 만들기 |
| GPT 탐색 페이지 | GPT 탐색 → 우측 상단 `+ 만들기` 버튼 |

### GPT 구성 요소 (SlidePro for Computer Science 예시)

| 구분 | 항목 | 내용 |
|------|------|------|
| **만들기** | 역할 정의 | "You are a professional computer science tutor who specializes in creating PowerPoint presentation content for undergraduate students." |
| **구성** | 이름 | SlidePro for Computer Science |
| **구성** | 설명 | A GPT for generating technical PowerPoint content for CS majors |
| **구성** | 지침 | 슬라이드 구조(제목/소제목/설명/코드블록/코드설명), 대상 학년, 기본 슬라이드 수(10) 지정 |
| **구성** | 대화 스타터 | "Make 10 detailed slides explaining CNN" 등 |
| **구성** | 기능 | 웹 검색, 캔버스, DALL-E 이미지 생성, 코드 인터프리터 |

### GPT 수정 & 공유
- **수정**: 구성 탭에서 지침 업데이트 → 오른쪽 [업데이트] 버튼 클릭
- **공유 범위**: GPT 스토어 공개 / 초대된 사람만 / 나만 보기
- **한글 PDF 지원**: 한글 폰트(NanumGothic 등)를 `지식`에 업로드 후 지침에 명시
- **프로필 이미지**: 왼쪽 상단 `+` 버튼으로 GPT 대표 아이콘 등록

### 다양한 맞춤형 GPT 주제 20선 (일부)

| # | GPT 주제 | 주요 기능 |
|---|----------|----------|
| 1 | 대학 수업 보조 GPT | 슬라이드, 시험지, 커리큘럼 설계 |
| 2 | AI 코딩 튜터 GPT | 실습 중심 코드 설명, 디버깅 |
| 6 | 생산성 코치 GPT | GTD 기반 일정/주간 계획 관리 |
| 10 | 해외 여행 가이드 GPT | 일정, 맛집, 교통/문화 설명 |
| 15 | 개발자 도우미 GPT | API 문서 요약, 샘플 코드 생성 |

### 공공데이터 분석 GPT 생성 예시
- **역할**: 공공데이터 기반 데이터 분석 전문가
- **지침 핵심**: pandas/matplotlib/seaborn 코드 제공, 시각화 한글 폰트 포함
- **대화 스타터**: "이 CSV 파일 요약해줘", "서울과 부산 데이터 비교해줘"
- **링크**: https://url.kr/drkmzd

---

## 핵심 정리

- ChatGPT 데스크탑 앱은 브라우저 없이 빠르게 접근할 수 있는 독립 실행형 도구
- 맞춤형 GPT는 **이름 → 설명 → 지침 → 대화 스타터 → 기능** 순서로 구성
- 지침을 구체적으로 작성할수록 GPT 품질이 향상됨
- 한글 PDF 출력이 필요한 경우 한글 폰트 파일을 지식에 업로드
