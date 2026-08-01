# axlab-oneday-starter

바이브코딩 원데이 클래스 진행용 스타터 패키지입니다. 이 폴더를 Claude Code에서 열면, Claude가 `CLAUDE.md`를 읽고 수업을 단계별로 안내합니다.

## 시작하는 법
1. Claude Code Desktop을 설치하고 로그인합니다.
2. 빈 `my-service` 폴더를 만들고, 새 Claude Code 세션에서 그 폴더를 엽니다.
3. Claude에 이렇게 부탁하세요:
   > 이 폴더에 수업 패키지 받아줘: https://github.com/yscriuf/axlab-oneday-starter.git

   Claude가 `git clone https://github.com/yscriuf/axlab-oneday-starter.git .` 로 **현재 폴더에 flat하게** 받아 수업을 시작합니다. (끝의 `.`이 "현재 폴더로"라는 뜻 — 하위 폴더를 만들지 않아야 루트 `CLAUDE.md`가 자동 로드됩니다.)
4. 이후 Claude의 안내를 따라가면 됩니다.

> `steps/`, `PROGRESS.md`, 진행 규칙, 이 안내는 수업이 끝나면 정리(삭제)됩니다.
