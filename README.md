# AI 브랜드 가이드라인 생성기

브랜드 정보를 입력하면 AI가 완성된 브랜드 가이드라인을 자동으로 만들어주는 웹 애플리케이션입니다.

## 🔗 라이브 데모

**[https://ldjwj.github.io/brand-genA-2603/](https://ldjwj.github.io/brand-genA-2603/)**

## 주요 기능

- **브랜드 퍼스널리티** — 브랜드를 사람처럼 표현한 성격과 SNS 말투 예시
- **컬러 팔레트** — 브랜드에 어울리는 Primary / Secondary / Accent 색상
- **타이포그래피** — 헤드라인 / 본문 / 강조용 Google Fonts 추천
- **브랜드 보이스** — DO / DON'T 가이드
- **로고 방향성** — 로고 스타일 설명 + Midjourney 프롬프트 자동 생성
- **슬로건 후보** — 브랜드에 맞는 슬로건 3개 제안
- **PDF 저장** — 생성된 가이드라인을 PDF로 다운로드

## 사용 방법

1. [OpenAI API Key](https://platform.openai.com/api-keys) 준비
2. 위 라이브 데모 URL 접속
3. 브랜드 이름, 타겟 고객, 한 줄 소개, 분위기 키워드 입력
4. **브랜드 가이드라인 생성하기** 버튼 클릭
5. 결과 확인 후 PDF로 저장

> API Key는 페이지를 새로고침하면 자동으로 사라지며, 서버에 저장되지 않습니다.

## 기술 스택

- Vanilla HTML / CSS / JavaScript (단일 파일)
- OpenAI GPT-4o API
- Google Fonts
- html2pdf.js

## 로컬 실행

별도의 설치 없이 `index.html` 파일을 브라우저에서 바로 열어 사용할 수 있습니다.
