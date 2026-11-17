# 프로필 구성 참고

2026-11-17에 다음 공개 README를 실제 조회하고, 정보 구성과 표현 방식을 비교했습니다.
프로젝트 설명과 수치는 firstsm41의 기존 공개 포트폴리오와 저장소에서 가져왔습니다.
배너는 문항 풀이·병원 디스플레이·POS라는 본인의 프로젝트 주제로 새로 제작했습니다.

| 참고 | 관찰한 구성 | 이번 프로필의 적용 방향 |
|---|---|---|
| [Anthony Fu](https://github.com/antfu/antfu) | 짧은 링크 탐색 | 상단 Portfolio / Selected work / Contact |
| [Anurag Hazra](https://github.com/anuraghazra/anuraghazra) | 소개 배너, 짧은 자기소개, 대표 저장소 | 고유 배너와 공개 프로젝트 중심 소개 |
| [DenverCoder1](https://github.com/DenverCoder1/DenverCoder1) | 제목·연락처·섹션을 분명하게 구분 | 탐색 가능한 섹션과 기술 영역 정리 |
| [Kent C. Dodds](https://github.com/kentcdodds/kentcdodds) | 이미지와 한 가지 메시지에 집중 | 배너의 일관된 메시지와 연락 경로 |
| [Simon Willison](https://github.com/simonw/simonw) | 현재 작업을 먼저 설명하고 표로 정보 배치 | 대표 작업에 역할·구현 근거·성과를 연결 |
| [ThePrimeagen](https://github.com/ThePrimeagen/ThePrimeagen) | 개발 관심과 정체성을 직접적인 문장으로 표현 | 간호학 전공과 실제 사용 환경을 연결한 자기소개 |
| [Sindre Sorhus](https://github.com/sindresorhus/sindresorhus) | 고유한 시각 언어와 직접 만든 작업으로 이동하는 링크 | 본인의 프로젝트 주제를 사용한 고유 이미지 |
| [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme) | 여러 유형의 프로필과 도구 비교 | 배너·기술·프로젝트 구성의 균형 점검 |

## 구성 원칙

- 방문자가 무엇을 만드는 개발자인지 먼저 알 수 있게 합니다.
- 대표 개인 작업과 팀 프로젝트를 구분합니다.
- 수치는 공개 포트폴리오에서 확인된 값만 사용합니다.
- 공개되지 않은 저장소·업무 자료는 포함하지 않습니다.
- 자동 갱신을 위한 GitHub Actions는 추가하지 않습니다.
- 프로필에서 실행되지 않는 CSS·JavaScript 대신 GitHub가 렌더하는 Markdown·HTML을 사용합니다.
- 다른 프로필의 이미지나 소개 문장을 복제하지 않습니다.

## 파일

- `README.md`: 프로필 본문
- `assets/header.svg`: 프로필용 환영 배너
- `assets/header.png`: 이전 포트폴리오형 배너 (프로필 본문에는 표시하지 않음)
- `docs/profile-settings.md`: GitHub 계정 화면에 적용할 설정 안내

## 프로필형 구성으로 조정

추가로 [Madplay](https://github.com/madplay/madplay),
[Doputer](https://github.com/doputer/doputer),
[Capsule Render 작성자](https://github.com/kyechan99/kyechan99)의 실제 README도 확인했습니다.
사용자가 제공한 예시처럼 환영 배너 → 짧은 자기소개 → 기술 배지 → 활동 통계 → 짧은 프로젝트 링크 순서로 바꿨습니다.
긴 구현 설명과 화면 캡처는 포트폴리오 저장소에서 확인하게 했습니다.

통계는 [GitHub Profile Summary Cards](https://github.com/vn7n24fzkq/github-profile-summary-cards)의 공개 API를 사용합니다.
적용 시 실제 firstsm41의 SVG 응답을 확인했으며, 인증 토큰·비공개 저장소 정보나 별도의 GitHub Actions는 사용하지 않습니다.
공개 활동 집계와 GitHub 계정 전체 기여 수는 다를 수 있습니다.
