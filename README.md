# かな道場 (카나 도장)

하루 5분씩 히라가나·가타카나 92자를 배우는 학습 앱입니다. iPhone·iPad에서 홈 화면에 추가해 앱처럼 쓸 수 있습니다.

- 글자 카드 학습: 한국어 연상법과 일본어 원어민 발음
- 퀴즈 10문제: 7초 제한, 콤보 보너스, 듣기 문제
- 따라쓰기: 손가락으로 쓰면 자동 채점
- 오프라인 사용 가능, 학습 기록은 기기에 저장

## GitHub Pages로 배포하기

1. GitHub에서 새 저장소(Repository)를 만듭니다. 예: `kana-dojo`, **Public**
2. 이 폴더의 파일을 모두 업로드합니다 (`Add file` → `Upload files`)
   - `index.html`, `manifest.webmanifest`, `sw.js`, `favicon.png`, `.nojekyll`, `icons/` 폴더
3. 저장소의 `Settings` → `Pages` → Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 지정하고 `Save`
4. 1~2분 뒤 `https://<내아이디>.github.io/kana-dojo/` 주소가 열립니다

## iPhone·iPad에 설치하기

1. 위 주소를 **Safari**로 엽니다
2. 공유 버튼(□↑) → **홈 화면에 추가**
3. 홈 화면의 「かな道場」 아이콘으로 실행합니다

## 업데이트

`index.html`을 새 버전으로 바꿔 올리면, 앱을 다시 열 때 자동으로 반영됩니다.
