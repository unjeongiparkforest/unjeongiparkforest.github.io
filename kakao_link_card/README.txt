# 카카오톡 이미지 링크 카드

## 최초 1회 설정
1. GitHub에서 `kakao-link-card`라는 Public 저장소를 만듭니다.
2. 이 ZIP의 `index.html`, `banner.png` 두 파일을 저장소 최상위에 업로드합니다.
3. GitHub 저장소의 Settings → Pages로 이동합니다.
4. Build and deployment에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, 폴더를 `/(root)`로 선택하고 Save합니다.
6. 생성된 주소는 보통 `https://내아이디.github.io/kakao-link-card/` 형태입니다.
7. index.html의 `YOUR-GITHUB-ID` 두 곳을 실제 GitHub 아이디로 바꾸고 저장합니다.

## 카카오톡에서 사용
완성된 GitHub Pages 주소를 오픈채팅방에 전송합니다.
카카오톡이 링크 미리보기를 생성하면 banner.png가 카드 이미지로 표시됩니다.
사용자가 링크 미리보기 카드를 누르면 GitHub Pages를 거쳐 아래 주소로 이동합니다.

https://consent.taesunglaw.com/consent/UIF01/14

## 이미지 변경
`banner.png`를 같은 이름의 새 이미지로 교체하면 됩니다.

주의: 카카오톡이 이전 링크 미리보기를 캐시할 수 있습니다. 이미지가 즉시 바뀌지 않을 경우 URL에 `?v=날짜` 같은 값을 붙여 새 URL로 공유하는 방식이 유용합니다.
