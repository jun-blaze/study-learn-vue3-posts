# Vue 3 Posts Practice

Vue 3와 Vue Router로 게시글 화면 구조와 SPA 라우팅을 연습하는 프런트엔드 학습 프로젝트다.

## 기술 구성

| 영역 | 기술 |
|---|---|
| UI | Vue 3, Bootstrap, Bootstrap Icons |
| 개발 서버·빌드 | Vite |
| 코드 품질 | ESLint, Prettier |

## 구조

| 경로 | 내용 |
|---|---|
| `src/layouts/` | 공통 헤더와 화면 레이아웃 |
| `src/views/` | 홈과 소개 화면 |
| `src/router/` | 클라이언트 라우팅 설정 |
| `src/assets/` | 공통 스타일과 이미지 |

## 실행

```bash
npm ci
npm run dev
```

## 검증

```bash
npm run lint
npm run build
```

백엔드 연동보다 Vue 애플리케이션의 기본 구조와 화면 전환 학습에 초점을 둔다.
