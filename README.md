# 마인크래프트 모드팩서버 전용구동기

마인크래프트 모드팩 서버를 Windows 환경에서 쉽게 설치하고 실행하기 위한 전용 구동기입니다.

복잡한 명령어 입력 없이, 모드팩 서버용 ZIP URL을 입력하고 설치 버튼을 누르면 서버 파일을 다운로드하고 압축 해제한 뒤 실행 가능한 서버 파일을 자동으로 탐색합니다.

---

## 주요 기능

- 모드팩 서버용 ZIP URL 직접 입력
- ZIP 파일 자동 다운로드
- 서버 설치 폴더 자동 생성
- ZIP 압축 해제
- `run.bat`, `start.bat`, `launch.bat`, `server.jar`, `neoforge*.jar`, `forge*.jar` 자동 탐색
- Java 8 / 17 / 21 / 25 런타임 선택 지원
- 메모리 할당 Slider 지원
- 서버 실행 / 중지 / 재시작
- 실시간 서버 로그 출력
- Windows 방화벽 TCP 포트 자동 등록
- 설정 저장 / 불러오기

---

## 지원 환경

- 운영체제: Windows
- 권장 실행 방식: 관리자 권한 실행
- 개발 기준: .NET 8 WPF
- 기본 서버 포트: TCP 25565

---

## 폴더 구조

프로그램은 아래와 같은 폴더 구조를 사용합니다.

```text
MinecraftModpackLauncher/
├─ MinecraftT2Launcher.exe
├─ Assets/
│  └─ t2_hosting_banner_1244x70.png
├─ runtimes/
│  ├─ java8/
│  ├─ java17/
│  ├─ java21/
│  └─ java25/
├─ servers/
├─ downloads/
├─ config/
└─ logs/
