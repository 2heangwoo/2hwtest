Furniture AR Viewer - USDZ Web Version

업로드할 파일
1. index.html
2. 1234.usdz

이번 버전은 웹에서도 GLB가 아니라 1234.usdz 자체를 Three.js USDZLoader로 불러옵니다.
따라서 USDZ 안에 포함된 텍스처/맵핑을 웹 뷰어에서도 사용합니다.

Netlify 사용:
폴더 또는 ZIP의 index.html + 1234.usdz를 함께 배포하세요.

중요:
- 로컬 file:// 더블클릭 테스트보다 Netlify HTTPS에서 테스트하세요.
- 웹 3D 로딩에는 인터넷 연결이 필요합니다(Three.js CDN 사용).
- iPhone/iPad Safari의 AR 버튼은 같은 1234.usdz를 Quick Look으로 엽니다.
