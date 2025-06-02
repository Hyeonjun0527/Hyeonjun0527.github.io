# 자기소개 웹사이트

간단하고 심플한 디자인의 개인 자기소개 웹사이트입니다.

## 구성

- **index.html**: 메인 자기소개 페이지 (3개 탭: 소개, 기술, 경력)
- **projects.html**: 프로젝트 소개 페이지
- **contact.html**: 연락처 정보 페이지
- **styles.css**: 칙칙하고 심플한 디자인의 스타일시트

## 기능

### 메인 페이지 (index.html)
- 반응형 디자인
- jQuery를 활용한 3개 탭 동적 전환 (소개/기술/경력)
- 부드러운 페이드 효과
- 프로필 이미지 호버 효과
- 스킬 카테고리 상호작용

### 프로젝트 페이지 (projects.html)
- 프로젝트 필터링 기능 (전체/React/Vue.js/Vanilla JS)
- 프로젝트 카드 호버 효과
- 기술 스택 태그 클릭 상호작용
- 순차적 페이드인 애니메이션
- GitHub/Demo 링크 클릭 처리

### 연락처 페이지 (contact.html)
- jQuery 폼 유효성 검사
- 실시간 에러 메시지 표시
- 포커스 효과
- 연락처 항목 호버 효과
- 일정 정보 페이드인 효과

## jQuery 기능들

- **탭 전환**: 부드러운 fadeIn/fadeOut 효과
- **폼 검증**: 실시간 유효성 검사 및 에러 표시
- **필터링**: 프로젝트 카테고리별 필터링
- **애니메이션**: 호버, 클릭, 페이드 효과
- **상호작용**: 다양한 클릭/호버 이벤트 처리

## GitHub Pages 배포 방법

1. 이 저장소를 GitHub에 업로드
2. Settings > Pages로 이동
3. Source를 "Deploy from a branch"로 설정
4. Branch를 "main"으로 선택
5. 몇 분 후 `https://[사용자명].github.io/[저장소명]`에서 사이트 확인

## 커스터마이징

- `index.html`, `projects.html`, `contact.html`에서 개인 정보 수정
- `styles.css`에서 색상 및 스타일 변경
- 이미지를 추가하려면 `.placeholder-img` 클래스를 실제 이미지로 교체

## 사용된 기술

- HTML5
- CSS3 (Grid, Flexbox)
- Vanilla JavaScript (탭 기능)

## 라이선스

MIT License 