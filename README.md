# 우리집 냉장고

둘이 같이 쓰는 냉장고·식단·장보기·메모 앱. GitHub Pages로 열고, 데이터는 비공개 저장소의 `data.json`에 저장됩니다.

## 설치 (처음 한 번, PC 권장)

1. **앱 저장소 만들기**: GitHub에서 새 저장소 `fridge` 생성 (Public) → 이 폴더의 파일을 전부 업로드 (Add file → Upload files).
2. **Pages 켜기**: 저장소 Settings → Pages → Branch를 `main` / `(root)`로 저장. 1~2분 뒤 `https://<아이디>.github.io/fridge/` 주소가 생깁니다.
3. **데이터 저장소 만들기**: 새 저장소 `fridge-data` 생성 (**Private**, README 체크 하나만). 비워 둬도 앱이 처음 저장할 때 `data.json`을 만듭니다.
4. **토큰 만들기**: GitHub 프로필 → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token
   - Repository access: **Only select repositories → fridge-data**
   - Permissions → Repository permissions → **Contents: Read and write**
   - 만료 기간은 원하는 만큼 (만료되면 새로 만들어 다시 넣으면 됨)
5. **내 폰 연결**: 앱 주소를 열고 오른쪽 위 설정 → 이름·아이디·저장소(`fridge-data`)·토큰 입력 → 연결하고 저장.
6. **배우자 폰 연결**: 내 폰 설정에서 `연결 코드 복사` → 배우자에게 전송 → 배우자 폰에서 앱 열고 설정 → 이름 입력 후 `연결 코드 붙여넣기` → 코드로 연결.

## 홈 화면에 앱으로 추가
- 아이폰: Safari로 열기 → 공유 → 홈 화면에 추가
- 안드로이드: Chrome으로 열기 → 메뉴(⋮) → 홈 화면에 추가 / 앱 설치

## 참고
- 앱 저장소(`fridge`)는 공개라 아이콘 사진도 주소를 아는 사람은 볼 수 있어요. 냉장고·메모 데이터는 비공개 저장소에만 있습니다.
- 연결 코드와 토큰은 둘만 보는 곳에 보관하세요.
- 앱을 고친 뒤 `index.html`만 다시 올리면 됩니다. 데이터는 그대로 유지돼요.
