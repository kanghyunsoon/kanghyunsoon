# 강형순

Unity로 3D 공간과 게임을 만들고, Java·Spring으로 서버를 만듭니다.

올해는 웹에서 꾸민 부스를 Unity 월드에 불러오는 SSAFESTA와, AI가 만든 추리 사건을 서버에서 검사한 뒤 저장하는 Operation KOREA를 만들었습니다. 두 프로젝트에서 모두 팀장을 맡았습니다. 혼자 만든 Unity 게임을 Google Play에 출시하고 업데이트한 경험도 있습니다.

프로젝트별로 어떤 문제를 어떻게 풀었는지는 [노션 포트폴리오](https://lapis-tuna-1ef.notion.site/3ef2ff41a8f38167a96fdc7f8732f818)에 정리했습니다.

**주로 쓰는 기술**

| 기술 | 쓴 곳 |
| --- | --- |
| Unity(C#) · Netcode for GameObjects | SSAFESTA WebGL 월드·전용 서버·건물 모델 최적화, 사제의 길 출시 |
| Java · Spring Boot · MyBatis · MySQL | Operation KOREA 백엔드. API, 생성 결과 검사 코드, JUnit 테스트 |
| Gemini·OpenAI API · MCP · Codex · Claude Code | Operation KOREA 사건 생성, SSAFESTA 트러블 기록·이슈 공유 자동화, DUO |
| Git · GitLab · Jira | SSAFESTA에서 브랜치·커밋 규칙을 정하고 Jira로 일정 관리 |

**써 본 기술**

| 기술 | 쓴 곳 |
| --- | --- |
| Unreal Engine(C++) | 멀티플레이 TPS, 잠입 액션 RPG |
| React · TypeScript | 수어의 달인 게임 화면, DUO |
| Docker | SSAFESTA Unity 전용 서버를 이미지로 만들어 로컬에서 접속 확인 |
| GitHub Actions | Operation KOREA와 DUO 테스트를 푸시할 때마다 실행 |

## 대표 프로젝트

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/kanghyunsoon/SSAFESTA-Portfolio"><img src="imgs/project-ssafesta.jpg" alt="Unity WebGL로 옮긴 SSAFY 캠퍼스 11층과 축제 월드"></a>
      <p><b><a href="https://github.com/kanghyunsoon/SSAFESTA-Portfolio">SSAFESTA</a></b><br>
      <sub>Unity WebGL · Netcode · Linux 서버 / 6인 팀, 팀장</sub></p>
      <p>사용자가 웹에서 꾸민 부스를 Unity 월드에 불러오는 기능과, 여러 명이 같은 월드에 접속하는 전용 서버를 맡았습니다. 팀원이 만든 SSAFY 캠퍼스 11층 모델은 웹 브라우저에서 실행되도록 오브젝트를 2,043개에서 156개로 합쳤습니다. 팀장으로서 구현 전에 담당 범위, 완료 조건, Git 규칙을 팀원들과 정했고, Jira로 일정을 관리했습니다.</p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/kanghyunsoon/operation-seoul"><img src="imgs/project-operation-korea.jpg" alt="Operation KOREA 지도, 최종 추리, 결과 화면"></a>
      <p><b><a href="https://github.com/kanghyunsoon/operation-seoul">Operation KOREA</a></b><br>
      <sub>Java · Spring Boot · Gemini / 2인 팀, 팀장</sub></p>
      <p>AI가 실제 장소 정보로 추리 사건을 만들면, 서버가 그 사건을 검사한 뒤 저장하는 백엔드를 맡았습니다. 처음에는 범인이 용의자 목록에 없거나 정답이 단서에 그대로 드러나는 사건이 생성되어서, 생성 단계를 나누고 단계마다 검사 코드를 넣었습니다. 에피소드 생성·관리 테스트는 67개입니다.</p>
      <p><sub>SSAFY 1학기 프로젝트 우수상</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/kanghyunsoon/sign-language-game"><img src="imgs/project-sign-language.jpg" alt="수어의 달인 대표 이미지"></a>
      <p><b><a href="https://github.com/kanghyunsoon/sign-language-game">수어의 달인</a></b><br>
      <sub>TensorFlow·TFLite · React · WebRTC / 6인 팀</sub></p>
      <p>웹캠으로 인식한 손 모양을 게임 입력으로 쓰는 웹게임입니다. AI의 도움을 받아 지문자 인식 모델의 학습 스크립트를 작성하고 튜닝했습니다. 한 프레임만 잘못 인식된 결과가 판정에 들어가지 않도록, 최근 프레임들의 인식 결과와 유지 시간을 확인한 뒤 입력으로 확정하게 했습니다. 게임 선택 이후의 프론트엔드와 WebRTC 1:1 대전도 맡았습니다.</p>
      <p><sub><a href="https://sudal-play.vercel.app">서비스</a></sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/kanghyunsoon/PathOfPriestPortfolio"><img src="imgs/project-path-of-priest.jpg" alt="사제의 길 전투, 던전, 편성, 성장 화면"></a>
      <p><b><a href="https://github.com/kanghyunsoon/PathOfPriestPortfolio">사제의 길: 낮과 밤</a></b><br>
      <sub>Unity · C# · Firebase / 1인 개발</sub></p>
      <p>방치형 RPG를 혼자 만들어 Google Play에 출시했습니다. 로그인, 진행 저장, 광고, 결제를 연동했고, 출시 후에는 Android SDK 의존성 충돌과 회원 탈퇴 기능을 수정해 업데이트했습니다.</p>
      <p><sub><a href="https://play.google.com/store/apps/details?id=com.KHS.MonsterRaidIdle">Google Play</a> · <a href="https://youtu.be/jKvEW6LIzaw">플레이 영상</a></sub></p>
    </td>
  </tr>
</table>

## 지금 만들고 있는 것

**[DUO](https://github.com/kanghyunsoon/duo)** · TypeScript · 개인 오픈소스 · [npm](https://www.npmjs.com/package/@duo-director/cli)

AI 코딩 에이전트가 팀이 정한 규칙과 다르게 코드를 바꾸면, 어느 파일의 몇 번째 줄인지 알려 주는 도구입니다. SSAFESTA에서 같은 API 경로가 문서와 코드에 서로 다르게 적혀 있었는데, 이것을 통합할 때에야 발견한 일이 있어서 만들기 시작했습니다. 코드는 AI 코딩 에이전트와 함께 작성하고, 무엇을 검사할지와 테스트 기준은 제가 정합니다.

테스트는 Ubuntu, Windows, macOS에서 실행하고, npm에 배포하기 전에 패키지를 직접 설치해 CLI가 실행되는지 확인합니다.

## 그 밖의 프로젝트

<details>
<summary>Paws Diary · 멀티플레이 TPS · 잠입 액션 RPG</summary>

- [Paws Diary](https://github.com/kanghyunsoon/Paws-on-Keyboard): 관광데이터 공모전 프로젝트입니다. Ennoia에서 사진 분석, 장소 추천, 일기 작성, 그림 생성을 맡는 에이전트의 역할과 실행 순서를 정했고, Ennoia에서 바로 호출할 수 없던 Hugging Face 모델은 [FastAPI 프록시](https://github.com/kanghyunsoon/HF_ProxyAPI)로 연결했습니다.
- [멀티플레이 TPS](https://github.com/kanghyunsoon/NetworkShooterPortfolio): Unreal C++로 만든 멀티플레이 게임입니다. 서버가 캐릭터 콜리전을 발사 시점의 위치로 되돌려 명중 여부를 다시 판정하도록 구현했습니다.
- [잠입 액션 RPG](https://github.com/kanghyunsoon/StealthActionRPGPortfolio): 첫 Unreal 프로젝트입니다. 커버 이동, 발 위치 보정, Behavior Tree AI를 만들었습니다.

</details>

## 교육·수상

- SSAFY 15기 Java 풀스택 과정 (2026.01~)
- 서울게임아카데미 3D 게임 프로그래머 양성과정 수료
- SSAFY 15기 1학기 프로젝트 우수상 · Operation KOREA, 서울 16반 2등

<details>
<summary>상장 보기</summary>

<img src="imgs/ssafy_pierce.png" alt="Operation KOREA 팀의 SSAFY 1학기 프로젝트 우수상 상장" width="440" />

</details>
