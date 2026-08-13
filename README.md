# AlignDisplay 공개 페이지

macOS 유틸리티 **AlignDisplay**의 소개·지원 페이지입니다. App Store의 지원 URL과 마케팅 URL,
개인정보 처리방침 URL로 사용합니다.

- 공개 주소: https://sayakkk.github.io/AlignDisplay-web/
- 문의: dltkdi173@gmail.com

앱 소스 코드는 별도의 비공개 저장소에 있습니다. 이 저장소에는 페이지만 들어 있습니다.

## 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 페이지 전체. 외부 의존성 없이 단일 파일로 동작합니다. |
| `assets/` | 앱 아이콘과 스크린샷 |

## 갱신하는 법

새 버전을 낼 때는 `index.html`에서 두 곳을 고칩니다.

1. 헤더의 `버전 1.1` 배지
2. "업데이트 정보" 섹션에 새 `<div class="release">` 블록 추가

스크린샷은 앱 저장소의 `Tools/screenshot.sh`로 다시 만들어 `assets/`에 덮어씁니다.
`main`에 push하면 GitHub Pages가 1분 안에 반영합니다.
