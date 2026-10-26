# Team Dynamics 2027

정적 HTML 웹사이트. 원문 PDF를 포함하며 공개 배포 시 문서도 누구나 볼 수 있습니다.

## GitHub + Vercel 배포

1. GitHub에서 새 저장소를 생성합니다.
2. 이 폴더 **안의 내용 전체**(`index.html`, `viewer.html`, `docs/`, `vercel.json`)를 저장소 최상위에 업로드합니다. ZIP 파일 자체를 올리지 마세요.
3. Vercel의 New Project > Import Git Repository에서 저장소를 선택합니다.
4. Framework Preset: **Other**, Root Directory: `./`, Build Command: **비워 두기**, Output Directory: **비워 두기**로 설정하고 Deploy 합니다.
5. 배포 URL에서 `index.html`, `viewer.html?page=13&section=15`, `docs/Team_Dynamics_2027_v25_Master_Manual.pdf`가 열리는지 확인합니다.

## 주의

PDF에 내부 설계 및 예산 정보가 있습니다. 공개 전에 팀의 배포 허가를 확인하세요.
