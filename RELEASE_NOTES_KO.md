# JY File Cleaner v2.0 Beta — 공식 배포 안내

**개발자:** JYrun  
**배포 형태:** Windows 64비트 무료 ZIP, PyInstaller onedir  
**공식 블로그:** https://blog.naver.com/asdfgh1

## 다운로드

첨부된 **`JY_File_Cleaner_v2.0_Beta.zip`**을 다운로드하여 **전체 압축 해제**한 뒤, 내부의 `JY_File_Cleaner_v2.0_Beta.exe`를 실행하세요. EXE만 따로 복사하면 실행에 필요한 `_internal` 의존성 파일이 누락될 수 있습니다.

- ZIP: 35,848,893바이트 (약 34.19 MiB)
- ZIP SHA-256: `ba89b334b4ee1179cb2502535a912b01832bb0a1e5b626281d6374fd239fbebf`
- EXE SHA-256: `ace647201ca84a6bc1f5e4cc08c73c1fa85482c7da7e5446c8af9c5ab3d342f3`

## 인터넷 다운로드 호환성 (.NET MOTW 대응)

브라우저로 다운로드한 압축 파일에서 Windows Mark of the Web(`Zone.Identifier`)이 내부 DLL로 전파될 때 .NET CLR 어셈블리 로딩이 차단되던 문제를 해결했습니다. `loadFromRemoteSources` 활성화 설정(`.exe.config`) 및 진입점 내부 어셈블리 방어 로직을 적용하여, 사용자가 여러 DLL의 속성을 직접 차단 해제하거나 별도 스크립트를 실행하지 않아도 최신 8개 메뉴 WebView2 화면이 바로 실행되도록 보완했습니다.

- 최신 8개 메뉴 UI 실행에 Microsoft Edge WebView2 Runtime 필요 (Windows 10 일부 구버전 환경에서는 [공식 설치 페이지](https://go.microsoft.com/fwlink/p/?LinkId=2124703)를 통한 설치 필요)
- 실행 문제 발생 시 `%LOCALAPPDATA%\JY_File_Cleaner\logs\startup.log` 및 `startup_error.log` 확인
- Windows SmartScreen의 'Windows의 PC 보호' 경고가 나타날 수 있습니다. **공식 출처와 SHA-256을 확인**한 뒤 파일을 신뢰하는 경우에만 '추가 정보' → '실행'을 선택할 수 있습니다. 보안 기능을 끄지 마세요.

## 주요 기능

- 디스크·파일 정리 후보 분석과 보호 항목 구분
- 대용량 파일·폴더 TOP 20 및 폴더별 점유율
- 다운로드 폴더 파일 유형별 정리 계획
- SHA-256 기반 완전 중복 파일 검색
- 유사 사진 찾기 및 미리보기
- 파일명 일괄 변경·이미지 변환·EXIF 확인
- 폴더와 ZIP 내용 비교
- 한국어 UI, 안내 및 도움말

## 검증 결과와 한계

- 소스 자동 회귀 테스트 115개 실행·통과, 실패·건너뜀 0개 보고
- 정정된 ZIP 무결성과 GitHub Release 배포를 확인했으며, 다운로드본의 Zone.Identifier 환경에서 최신 WebView2 창 실행·종료 확인
- **Windows 10 64비트(22H2) 실기 검증** (Windows 11 실기 직접 검증은 별도로 수행하지 않음)
- 격리된 합성 테스트 파일 대상 백엔드 기능 및 휴지통 처리 확인
- 유사 사진 탐색은 회전·심한 크롭을 모두 인식하지 않으며 오탐·누락 가능성이 있음
- 본 프로그램은 특정 또는 모든 사용자 환경에서의 무결점 동작을 보증하지 않습니다.

**베타 버전입니다.** 실제 파일 이동·변경·정리 전에 결과를 확인하고 중요한 자료는 백업해 주세요. 처음 사용한다면 소량의 테스트 파일로 사용법을 익히는 것을 권장합니다.

[설치·상세 사용 안내](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/blob/main/INSTALL_KO.md) · [오류 제보](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/issues)

---

**Developed by JYrun**
