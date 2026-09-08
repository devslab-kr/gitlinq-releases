# GitLinq 다운로드

SVN에 익숙한 사용자를 위한 Windows Git 클라이언트입니다. 작성자와 변경 설명으로 로그를 확인하고, 중간에 반영한 내 변경 하나를 취소하는 과정을 안내합니다.

이 저장소는 **공개 배포 파일과 사용 안내**를 제공합니다. 앱 소스는 별도 비공개 저장소에서 관리합니다.

## 다운로드

[최신 Release](https://github.com/devslab-kr/gitlinq-releases/releases/latest)에서 원하는 파일을 선택하세요. [GitLinq 제품 페이지](https://devslab-kr.github.io/gitlinq/)에서도 받을 수 있습니다.

- **설치본:** `GitLinq-<버전>-windows-x64-setup.exe`
- **무설치본:** `GitLinq-<버전>-windows-x64-portable.zip` 전체를 풀고 `GitLinq.exe` 실행
- **한국어 사용 안내:** `GitLinq-<버전>-guide-ko.html`
- **파일 확인:** `SHA256SUMS.txt`와 명세·타사 고지를 함께 제공합니다.

Windows 10/11 x64와 Microsoft Edge WebView2 Evergreen Runtime이 필요합니다. Git은 자동 인식하거나 앱 설정에서 공식 Git 다운로드·오프라인 ZIP 가져오기로 준비할 수 있습니다. 코드 서명이 없는 미리보기 배포본입니다.

## 현재 제공하는 기능

- 작성자·설명 중심 로그와 내 변경 선택
- 선택한 변경의 취소 미리보기와 새 서버 취소 커밋
- 중단한 작업의 결과 확인
- 수정 중인 파일이 없는 작업 폴더에서 서버 변경 받기
- Git 경로 설정, 앱 전용 Git 준비, 회사 프록시·오프라인 Git 반입 설정

일상 커밋과 직접 충돌 편집은 개발 중입니다. 취소는 기존 서버 커밋을 지우지 않고 새 취소 커밋을 추가합니다.

## 업데이트

버전별 파일은 Releases에 게시합니다. 실행 중인 GitLinq를 닫은 뒤 새 설치본을 사용하거나 새 ZIP을 별도 폴더에 풀어 실행하세요. 설치본과 무설치본은 같은 Windows 계정의 앱 설정을 공유합니다.

## 문의

[이슈 등록](https://github.com/devslab-kr/gitlinq-releases/issues) 시 사용 중인 버전과 재현 단계를 알려주세요. 회사 코드·저장소 주소·인증 정보가 포함된 로그는 공개 이슈에 올리지 마세요.
