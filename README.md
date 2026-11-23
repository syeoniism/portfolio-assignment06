# 김서연 · syeoniism 포트폴리오 — 작문과제 06

`portfolio-0/portfolio-github`를 바탕으로 제작한 **별도 복사본**입니다. 기존 원본과 배포된 포트폴리오는 수정하지 않았습니다.

## 과제 지침과 반영 위치

과제 원문은 “대략적인 내용”을 제시하며, `+`가 붙은 결과·데모·소스 코드·이력서 PDF도 이번 복사본에 반영했습니다. 대표 프로젝트는 최소 1개이고, 이 복사본에는 3개가 있습니다.

| 항목 | 반영 내용 | 위치 |
|---|---|---|
| 닉네임 | syeoniism, 김서연 | 첫 화면 |
| 현재 관심 분야 | Web/App, Game Dev, HCI, Graphics | About |
| GitHub 링크 | 개인 프로필 및 프로젝트 저장소 | 첫 화면, 프로젝트, Contact |
| 대표 프로젝트 | BOOKUS, Career Balance, Glass Slash | Selected Projects |
| 문제 정의 | 각 프로젝트에서 해결하려는 불편·구현 목적 | 각 프로젝트의 Problem |
| 역할 | 본인의 담당 범위와 상세 기여 | Role, 상세 보기의 What I Did |
| 기술 | 실제 사용 기술과 오픈소스 | Stack, Key Features, 상세 보기 |
| 결과 | 완성 기능과 확인된 성능 | Outcome, 상세 보기 |
| 데모 링크 | Glass Slash 실제 플레이 | Glass Slash의 플레이 데모 |
| 앱·웹 화면 | 기존 실제 화면 이미지 | BOOKUS, Career Balance의 화면 보기 및 슬라이드 |
| 소스 코드 | 공개 GitHub 저장소 | 각 프로젝트의 소스 코드 |
| 이력서 PDF | 실제 PDF 파일, 다운로드 링크 2곳 | 첫 화면, Contact, assets/resume-kim-seoyeon.pdf |
| GitHub Pages | 정적 파일 및 상대경로 구성 | 배포 절차는 아래 참고 |
| 제출 파일 | 배포 완료 후 URL만 적은 텍스트 파일 | 정확한 파일명: 김서연-공작과제-06.txt |

## 원본 대비 변경

- **유지:** 원래 색상, 글꼴, 레이아웃, 사진, About 본문, 기존 프로젝트 이미지, Timeline, 캔버스 애니메이션, 스크롤 효과, 슬라이드, 상세 펼침, 이미지 확대.
- **보강:** 첫 화면에 닉네임·GitHub·이력서 다운로드, BOOKUS와 Career Balance에 문제 정의·역할·기술·결과를 명시했습니다.
- **추가:** 최신 공개 프로젝트 Glass Slash, 실제 플레이 링크, 기하 규칙 개념도, 이력서 PDF와 편집용 텍스트.
- **정리:** Contact의 Instagram 링크를 이력서 다운로드로 교체했습니다. 복사본에 불필요한 기존 `.git` 이력과 `tmp` 폴더는 포함하지 않았습니다.
- BOOKUS의 92.86%는 **테스트 이미지 112장**에서 얻은 정확도입니다. 실제 모든 사진에 적용되는 성능이나 서비스 전체 성과로 표현하지 않았습니다.
- BOOKUS와 Career Balance의 화면 보기는 **정적 이미지**입니다. 실행 가능한 웹 데모로 표시하지 않았습니다.
- Glass Slash 그림은 **게임 규칙 개념도**입니다. 실제 게임 화면 캡처로 표시하지 않았습니다.

## 로컬 확인

`index.html`을 브라우저로 열면 됩니다. 이 포트폴리오는 빌드나 패키지 설치가 필요 없는 HTML/CSS/JavaScript 정적 페이지입니다.

Python을 사용할 경우 이 폴더에서 다음을 실행할 수도 있습니다.

```powershell
python -m http.server 8000
```

이후 `http://localhost:8000`을 엽니다.

## 별도 GitHub Pages 배포

기존 포트폴리오 제출본을 보존하려면 **새 저장소**에 이 복사본만 올리면 됩니다. 예시 저장소 이름은 `portfolio-assignment06`이며 아직 생성하거나 배포하지 않았습니다.

1. GitHub 계정 `syeoniism`에서 새 Public 저장소를 만듭니다.
2. 이 폴더 **안의 내용**을 새 저장소 최상위에 업로드합니다. 저장소 루트에서 `index.html`, `styles.css`, `script.js`, `assets/`, `.nojekyll`이 보여야 합니다.
3. **Settings → Pages → Build and deployment → Deploy from a branch**를 선택합니다.
4. 기본 브랜치의 **/(root)**를 선택하고 저장합니다. 기본 브랜치가 `main`이라면 `main / (root)`입니다.
5. 배포 완료 후 Pages 설정에 표시된 **실제 주소**를 열어 화면·데모·PDF 다운로드를 확인합니다.
6. 과제 제출 파일의 이름은 **김서연-공작과제-06.txt**로 하고, 내용에는 확인된 배포 URL 한 줄만 넣습니다.

새 저장소 이름을 예시대로 사용했을 때 예상 주소는 `https://syeoniism.github.io/portfolio-assignment06/`입니다. **이것은 예상 주소이며 현재 배포 완료를 뜻하지 않습니다.** 실제 URL 확인 전에는 제출용 텍스트 파일을 만들지 않았습니다.

> 기존 저장소 `syeoniism/portfolio`의 원격 연결을 복사하지 않았습니다. 따라서 이 폴더를 열었다고 기존 사이트가 자동으로 덮어써지지 않습니다.

## 배포 전 확인 항목과 한계

| 확인 항목 | 기준 |
|---|---|
| 정보 정확성 | 확인된 GitHub README와 기존 포트폴리오에 근거하며, 미확인 수상·학점·취업 경력은 추가하지 않음 |
| 파일 경로 | 프로젝트명에 의존하는 절대경로 대신 상대경로 사용 |
| PDF | 실제 파일이 있고 다운로드 링크가 정상인지 확인 |
| 화면 | PC·모바일에서 프로젝트 설명과 새 링크를 확인 |
| 외부 링크 | 배포 후 GitHub, Glass Slash 플레이 링크 재확인 |
| 최종 제출 | 텍스트 파일에 URL 이외의 설명·제목·이름을 넣지 않음 |

프로젝트별 근거: [docs/content-sources.md](docs/content-sources.md). 편집용 이력서: [docs/resume.md](docs/resume.md).

외부 링크는 각 프로젝트 운영 상태에 따라 변경될 수 있습니다. BOOKUS와 Career Balance의 백엔드 실행 환경을 이 정적 사이트에 포함하거나 동작한다고 가정하지 않았습니다.
