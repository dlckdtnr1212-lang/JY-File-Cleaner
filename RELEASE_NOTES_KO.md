# JY File Cleaner v2.0 Beta — 첫 공개 배포 안내

**개발자:** JYrun  
**배포 형태:** Windows 64비트 무료 ZIP, PyInstaller onedir  
**공식 블로그:** https://blog.naver.com/asdfgh1

## 다운로드

첨부된 **`JY_File_Cleaner_v2.0_Beta.zip`**을 다운로드하여 **전체 압축 해제**한 뒤, 내부의 `JY_File_Cleaner_v2.0_Beta.exe`를 실행하세요. EXE만 따로 복사하면 실행에 필요한 `_internal` 의존성 파일이 누락될 수 있습니다.

- ZIP: 35,843,353바이트 (약 34.18 MiB)
- ZIP SHA-256: `6f752432008d75678215bcf5a31fb3e05b405cc3721f1305804ae4d1390ddfab`
- EXE SHA-256: `5fae2a4ed0b01cbc5cc4273f61b28461c655704d7184d8fc0420136235b8b790`

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
- 배포 ZIP 압축 무결성 및 실행·종료·재실행 확인
- Windows 10 64비트(22H2) 실기 검증
- 격리된 합성 테스트 파일 대상 백엔드 기능 및 휴지통 처리 확인
- Windows 11 실기와 WebView2 미설치 상태의 자동 폴백은 별도 검증하지 않음
- 유사 사진 탐색은 회전·심한 크롭을 모두 인식하지 않으며 오탐·누락 가능성이 있음

**베타 버전입니다.** 실제 파일 이동·변경·정리 전에 결과를 확인하고 중요한 자료는 백업해 주세요. 처음 사용한다면 소량의 테스트 파일로 사용법을 익히는 것을 권장합니다.

[설치·상세 사용 안내](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/blob/main/INSTALL_KO.md) · [오류 제보](https://github.com/dlckdtnr1212-lang/JY-File-Cleaner/issues)

---

**Developed by JYrun**
