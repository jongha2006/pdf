# StudySync 배포 안내 (GitHub Pages)

1. GitHub 로그인 후 New repository에서 `studysync` 이름으로 **Public** 저장소 생성 (README 자동 생성 선택 해제).
2. 저장소에서 Add file → Upload files를 누르고 이 폴더의 **파일 자체** (`index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `apple-touch-icon.png`, `.nojekyll`)를 최상위에 업로드. 폴더 통째로 업로드하지 않기.
3. Commit changes 클릭.
4. Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main, /(root) → Save.
5. 배포 완료 후 `https://사용자명.github.io/studysync/` 접속. 실제 주소는 Settings → Pages에서 확인.
6. 아이폰 Safari에서 사이트 접속 → 공유 → 홈 화면에 추가 → 추가.
7. 앱 실행 후 PDF 두 개를 선택해 저장 및 열람 테스트.

주의: GitHub 저장소에는 수업 PDF를 올리지 마세요. 앱에서 선택한 PDF는 기기 내부 IndexedDB에 저장됩니다. 브라우저 저장소가 삭제되면 자료가 사라질 수 있으므로 원본은 별도로 보관하세요. 최초 접속 및 라이브러리 캐시 구성에는 인터넷이 필요합니다. iOS 환경과 저장 공간에 따라 오프라인 사용이 달라질 수 있습니다. GitHub Pages 배포에는 몇 분 걸릴 수 있습니다.
