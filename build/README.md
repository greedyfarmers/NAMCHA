# 남차바르와전자 (NAMCHA BARWA ELECTRONICS) 홈페이지

정적 사이트입니다. 별도 빌드 과정 없이 그대로 배포할 수 있습니다.

## 구성
- `index.html` — 전체 사이트 (한 파일 안에 모든 페이지가 들어 있습니다)
- `support.js` — 렌더링 런타임
- `image-slot.js` — 이미지 자리 컴포넌트
- `assets/` — 로고, 사진, 영상

## 배포 (GitHub Pages)
1. 이 폴더의 내용을 저장소 루트에 올립니다.
2. Settings → Pages → Source를 `main` 브랜치 / `/ (root)`로 지정합니다.
3. 몇 분 후 `https://<계정>.github.io/<저장소>/` 로 접속됩니다.

## 외부 의존성 (CDN)
- Pretendard 웹폰트
- MapLibre GL (오시는 길 지도)

인터넷이 차단된 환경에서 쓰실 경우 두 파일을 내려받아 로컬 경로로 바꿔주세요.
