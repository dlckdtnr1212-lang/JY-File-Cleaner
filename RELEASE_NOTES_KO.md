# JY File Cleaner v2.0 Beta — Candidate 50 배포 안내

**개발자:** JYrun  
**형태:** Windows 10/11 64비트 대상 무료 ZIP 배포본 (Windows 10 64비트 실사용 확인)

## 다운로드

[공식 Release](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/releases/tag/v2.0-beta)에서 `JY_File_Cleaner_v2.0_Beta.zip`을 내려받고 전체 압축 해제한 뒤 `JY_File_Cleaner_v2.0_Beta.exe`를 실행하세요. `_internal` 폴더와 배포 구성 파일을 유지해야 합니다.

- Candidate 50 ZIP 크기: **35,892,468바이트**
- ZIP SHA-256: `893acd5d483c44558ea70b2201a9fa0a46675609933c7e7a7ea8ac9e7f4f686b`
- EXE SHA-256: `783727b56ba7e099e6ff204aac79f5af1a2cdf76199a6f93c8a7ea44b4eb7fd6`

## 이번 베타 수정판

이전 베타의 중복 파일 선택·정리 시뮬레이션 문제를 수정 대상으로 삼아 배포 후보를 갱신했습니다. 빈 폴더 탐색과 다운로드 정리 후 화면 갱신, 파일 위치 열기, 백업 비교 필터, OneDrive 보호 버튼의 사용 흐름을 점검했습니다.

기능은 대시보드, 디스크·파일 정리, 다운로드 스마트 정리, 중복 파일 탐색, 유사 사진 비교, 파일 편의 도구, 백업·폴더 비교, 설명서·정보의 8개 메뉴로 구성됩니다. 유사 동영상 탐색 기능은 제공하지 않습니다.

## 확인된 범위

- **사용자 직접 확인, Windows 10 64비트 Candidate 50:** ZIP 압축 해제 및 EXE 실행, D드라이브 빈 폴더 탐색, 다운로드 정리 후 자동 갱신, 한글·쉼표 포함 파일의 위치 열기, 백업 비교 필터, OneDrive 보호 파일 삭제 버튼 비활성화.
- **소스 대응 관계:** 배포 EXE의 보고된 로컬 소스 커밋 `ee15c61`은 현재 GitHub에서 조회되지 않습니다. GitHub의 문서·태그 스냅샷을 이 실행 파일의 소스와 동일하다고 보장하지 않습니다.
- **미검증:** Windows 11 실기, 다양한 PC의 다운로드 보안 표시(MOTW)와 SmartScreen 흐름, 전체 기능의 모든 입력·환경.

WebView2 Runtime이 없으면 [Microsoft 공식 페이지](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)에서 설치 여부를 확인하세요. SmartScreen 경고 시 공식 배포처와 해시를 확인하고 신뢰하는 경우에만 화면의 실행 옵션을 선택하세요. 보안 기능을 끄지 마세요.

정리 전 시뮬레이션과 보호 사유를 확인하고 원본을 최소 한 개 남기세요. Windows 휴지통에서의 복원은 설정과 상태에 따라 달라질 수 있습니다.

[설치·사용 안내](INSTALL_KO.md) · [오류 제보·개선 의견](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/issues)

**Developed by JYrun** · [공식 블로그](https://blog.naver.com/asdfgh1)
