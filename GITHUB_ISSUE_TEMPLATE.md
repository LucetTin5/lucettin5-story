# [Epic] 마크다운 블로그 프로젝트 스캐폴딩

## 📋 프로젝트 개요

Tanstack Start, Tailwind v4, Shadcn UI, React 19, Bun을 활용한 마크다운 기반 블로그 구축 프로젝트

## 🛠 기술 스택

- **프레임워크**: Tanstack Start (React 19)
- **런타임**: Bun
- **스타일링**: Tailwind CSS v4
- **UI 컴포넌트**: Shadcn UI
- **콘텐츠 관리**: Markdown
- **폰트**: Pretendard
- **테마**: 다크모드 전용, 녹색 계열

## ✨ 주요 기능

- 📝 **Posts**: 마크다운 파일 기반 블로그 포스팅
- 🔍 **Search**: 포스트 검색 기능
- 📧 **Contact**: 연락처 페이지
- 🌐 **다국어**: 한국어(메인), 영어

## 📂 프로젝트 구조

```
lucettin5-story/
├── app/
│   ├── routes/                    # 라우트 정의
│   ├── components/                # 재사용 컴포넌트
│   ├── utils/                     # 유틸리티 함수
│   └── styles/                    # 스타일 파일
├── content/posts/                 # 마크다운 포스트
│   ├── ko/                        # 한국어 포스트
│   └── en/                        # 영어 포스트
├── public/fonts/                  # Pretendard 폰트
└── 설정 파일들
```

## 🎯 구현 단계

### Phase 1: 프로젝트 초기 설정
- [ ] Tanstack Start 프로젝트 초기화
- [ ] Bun 패키지 매니저 설정
- [ ] TypeScript 설정
- [ ] ESLint/Prettier 설정

### Phase 2: 스타일링 설정
- [ ] Tailwind CSS v4 설치 및 설정
- [ ] 다크모드 녹색 테마 색상 팔레트 정의
- [ ] Pretendard 폰트 설치 및 적용
- [ ] 글로벌 스타일 설정

### Phase 3: Shadcn UI 통합
- [ ] Shadcn UI 초기화
- [ ] 기본 컴포넌트 설치 (Button, Card, Input, Navigation Menu 등)

### Phase 4: 레이아웃 구성
- [ ] 기본 레이아웃 컴포넌트 생성
- [ ] 헤더/네비게이션 구현
- [ ] 푸터 구현
- [ ] 반응형 레이아웃 적용

### Phase 5: 마크다운 시스템
- [ ] 마크다운 파싱 라이브러리 설정 (remark/rehype)
- [ ] 프론트매터 파싱
- [ ] 코드 하이라이팅 설정
- [ ] 마크다운 렌더러 컴포넌트 구현

### Phase 6: 포스트 기능
- [ ] 포스트 목록 페이지
- [ ] 개별 포스트 페이지
- [ ] 포스트 메타데이터 처리
- [ ] 포스트 카드 컴포넌트

### Phase 7: 검색 기능
- [ ] 검색 인터페이스 구현
- [ ] 클라이언트 사이드 검색 로직
- [ ] 검색 결과 페이지

### Phase 8: Contact 페이지
- [ ] 연락처 폼 UI
- [ ] 폼 유효성 검사

### Phase 9: 다국어 지원
- [ ] i18n 유틸리티 구현
- [ ] 언어 전환 UI
- [ ] 한국어/영어 콘텐츠 라우팅

### Phase 10: 최적화 및 배포
- [ ] SEO 메타태그 설정
- [ ] OG 이미지 설정
- [ ] 성능 최적화
- [ ] 빌드 및 배포 설정

## 🎨 디자인 가이드

### 색상 팔레트 (녹색 다크모드)
```css
--background: #0a0f0a;
--foreground: #e8f5e9;
--primary: #4caf50;
--primary-hover: #66bb6a;
--secondary: #1b5e20;
--accent: #81c784;
--muted: #1b2e1b;
--border: #2d4a2d;
```

### 폰트
- Primary: Pretendard

### 테마
- 다크모드 전용
- 녹색 계열 강조색

## 📦 주요 패키지

- `@tanstack/start` - 프레임워크
- `react@19` - UI 라이브러리
- `tailwindcss@4` - 스타일링
- `remark` / `rehype` - 마크다운 처리
- `gray-matter` - 프론트매터 파싱
- `date-fns` - 날짜 처리

## 📝 참고사항

- 모든 UI는 다크모드 전용으로 설계
- 접근성(a11y) 고려 필수
- 모바일 퍼스트 반응형 디자인
- SEO 최적화 필수
- 빠른 로딩 속도 목표

## 🔗 관련 문서

- [상세 계획서](./PROJECT_SETUP_PLAN.md)

---

**Labels**: `epic`, `enhancement`, `documentation`
**Priority**: High
**Assignee**: @lucettin5
