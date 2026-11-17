# JY File Cleaner v2.0 Beta — 첫 공개 배포 안내

**개발자:** JYrun  
**배포 형태:** Windows 64비트 무료 ZIP, PyInstaller onedir  
**공식 블로그:** https://blog.naver.com/asdfgh1

## 다운로드

첨부된 **`JY_File_Cleaner_v2.0_Beta.zip`**을 다운로드하여 **전체 압축 해제**한 뒤, 내부의 `JY_File_Cleaner_v2.0_Beta.exe`를 실행하세요. EXE만 따로 복사하면 실행에 필요한 `_internal` 의존성 파일이 누락될 수 있습니다.

- ZIP: 35,846,859바이트 (약 34.19 MiB)
- ZIP SHA-256: `4eb2e2f0bcf368367fdd8d96cb9d342501aa09f422b0cd423a99138fee23205d`
- EXE SHA-256: `b74fb9cdb1bc970a7f5d1b81d41a17373b0f5cabb9c51e55137285af298ee99e`

## 2026-11-17 배포본 정정

기존 배포 EXE에서 최신 WebView2 화면 대신 구형 Tkinter 화면이 표시된 문제를 확인하여, 시작 전 런타임 점검·오류 안내 및 사용자 로그 저장을 보강한 새 ZIP으로 교체했습니다. 개발보고서상 GitHub 재다운로드 후 최신 WebView2 창 실행을 확인했습니다. 다만 모든 사용자 PC에서의 동작을 보증하지 않습니다.

- 최신 8개 메뉴 UI 실행에 Microsoft Edge WebView2 Runtime 필요
- 실행 문제 발생 시 `%LOCALAPPDATA%\JY_File_Cleaner\logs\startup.log` 확인
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
- 정정된 ZIP 무결성과 GitHub Release 교체를 확인했으며, 개발보고서상 재다운로드 후 최신 WebView2 창 실행·종료 확인
- Windows 10 64비트(22H2) 실기 검증
- 격리된 합성 테스트 파일 대상 백엔드 기능 및 휴지통 처리 확인
- Windows 11 실기와 WebView2 미설치 상태의 자동 폴백은 별도 검증하지 않음
- 유사 사진 탐색은 회전·심한 크롭을 모두 인식하지 않으며 오탐·누락 가능성이 있음

**베타 버전입니다.** 실제 파일 이동·변경·정리 전에 결과를 확인하고 중요한 자료는 백업해 주세요. 처음 사용한다면 소량의 테스트 파일로 사용법을 익히는 것을 권장합니다.

[설치·상세 사용 안내](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/blob/main/INSTALL_KO.md) · [오류 제보](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/issues)

---

**Developed by JYrun**
