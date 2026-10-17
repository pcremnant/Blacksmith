# 대장장이 게임 개발 문서

한국어 기획 문서 묶음 v0.1 / 2026-10-17.

예정 개발 폴더: `C:\개인플젝\대장장이`.

## 시작하기

Unity 프로젝트는 `Blacksmith/`에 있다. Unity Hub에서 Add → Add project from disk로 이 폴더를 선택하고 Unity 6000.2.12f1로 연다. 현재는 빈 프로젝트이며 플레이 가능한 공정은 아직 없다. 최초 배치 실행의 패키지 임포트·스크립트 컴파일·정상 종료를 확인했다. 렌더링 방식과 대상 플랫폼은 아직 미정이다.

1. [GDD.md](GDD.md)에서 전체 방향을 읽는다.
2. [근거·복원 한계](docs/sources.md)와 [결정 기록](docs/decisions.md)에서 확정 여부를 확인한다.
3. [개발 계획](docs/development-plan.md)과 [미정 질문](docs/open-questions.md)으로 첫 구현 범위를 고른다.
4. Codex 작업 시 [AGENTS.md](AGENTS.md)의 개발 지침을 적용한다.

## 문서 지도

- [튜토리얼](docs/tutorial.md)
- [공정 평가·급여](docs/evaluation-and-pay.md)
- [기술 설계](docs/technical-design.md)
- 미니게임: [용해](docs/minigames/melting.md), [주조](docs/minigames/casting.md), [단조](docs/minigames/forging.md), [조립](docs/minigames/assembly.md), [연마](docs/minigames/polishing.md)

## 사용 시 주의

초기 기획 문서는 확인 가능한 최근 사용자 발언 5개에 기반한다. 원대화 전체와 assistant 본문은 확보되지 않았다. 이후 결정은 결정 기록에 추가한다. **확정/제안/미정** 표시는 모든 문서에서 같은 의미를 가진다.

ZIP은 폴더 내부 파일을 루트에 담는다. 개발 폴더에서 압축을 풀면 `GDD.md`, `AGENTS.md`, `docs/`가 바로 배치된다. 기존 동명 파일이 있으면 먼저 내용을 비교하고 병합한다.
