# NEXT BRANDING — Static Site (Free Hosting)

## 1) 로컬에서 확인
- 폴더에서 `index.html` 더블클릭으로 열어도 됩니다.
- 더 안정적으로 보려면 VSCode + Live Server 추천.

## 2) GitHub Pages로 무료 배포 (추천)
1. GitHub에 로그인 후 새 Repository 생성 (Public)
   - 예: `nextbranding-site`
2. 이 폴더의 파일들을 레포지토리에 업로드 (루트에 index.html이 있어야 함)
3. GitHub 레포 → Settings → Pages
4. Source: `Deploy from a branch`
5. Branch: `main` / Folder: `/ (root)` 선택 → Save
6. 잠시 후 `https://<username>.github.io/<repo>/` 로 접속

## 3) 바꿔야 할 것 (최소)
- `contact.html` 안의 TO_EMAIL 값을 실제 이메일로 변경
- 문구/케이스/로고는 필요할 때 교체

## 4) 확장 (나중에)
- 폼 서버 전송: Netlify Forms / Firebase / Supabase로 확장 가능
- 다국어, CMS: 구조 그대로 붙일 수 있게 만들어둠
