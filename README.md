# OX2Lab skills

옥스투랩 AI Skills 모음 저장소입니다.

이 저장소는 직접 수정하지 않으며,
`ox2-skills` 프로젝트의 변경 사항이 자동으로 동기화됩니다.

## 스킬 설치

`--agent universal` 플래그는 대부분의 에이전트가 사용하는 표준 `.agents/skills` 폴더에 설치합니다.

`-y(또는 --yes)` 플래그는 모든 확인 옵션을 승인(Yes)으로 넘어갑니다.

`-g`(Global) 옵션을 붙이지 않으면 기본적으로 **Project 범위(로컬 프로젝트 폴더)**에 스킬을 설치하도록 동작합니다.

### 전체 스킬 설치
프로젝트에 모든 스킬을 설치하려면 아래 명령어를 실행하세요.
```bash
npx skills add ox2lab/skills --agent universal --yes --skill '*'
```

### 특정 스킬만 설치
```bash
npx skills add ox2lab/skills --agent universal --yes --skill '스킬 이름' --skill '스킬 이름'
```

### 예시
```bash
npx skills add ox2lab/skills --agent universal --yes --skill 'ox2-harness' --skill 'ox2-grill-me'
```

## 스킬 업데이트
업데이트하려면 아래 명령어를 실행하세요.
```bash
npx skills update
```
