My Kitchen Diary v0.3 — iPhone PWA

1. GitHub에서 공개 저장소 my-kitchen-diary 생성
2. 이 폴더 안의 6개 파일을 저장소 루트에 업로드 (폴더 자체가 아닌 파일들)
3. Settings > Pages > Deploy from a branch > main / (root) > Save
4. 배포된 https://사용자이름.github.io/my-kitchen-diary/ 를 아이폰 Safari에서 열기
5. 공유 > 홈 화면에 추가 > 추가

중요: 데이터는 서버가 아니라 해당 아이폰/브라우저에 저장됩니다. 다른 기기와 자동 동기화되지 않습니다. 홈 화면 앱과 Safari는 저장 공간이 분리될 수 있으므로 기존 기록은 백업 내보내기/가져오기를 사용하세요. 사진은 최대 6장, 브라우저 저장 한도에 주의하고 정기적으로 JSON 백업하세요. PWA 오프라인 실행은 첫 온라인 접속 후 설치가 끝난 경우에만 가능할 수 있습니다. GitHub Pages는 소스 코드가 공개됩니다.

V0.4: Calendar view with date filters and same-name recipe history comparison. Existing v0.3 localStorage and backup files remain compatible. Upload all files to the same GitHub Pages repository root.
