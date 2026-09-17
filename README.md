# Eunsu Kong — UX/UI Portfolio

Vite 기반 정적 사이트. React 런타임(`public/support.js`)이 페이지의 컴포넌트 템플릿과 로직을 렌더합니다.

## 로컬 실행
```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # dist/
npm run preview
```

## Vercel 배포
1. 이 폴더를 GitHub 저장소에 push
2. Vercel → New Project → 저장소 선택
3. Framework: **Vite** / Build: `npm run build` / Output: `dist` (자동 감지)

CLI로 바로 배포하려면:
```bash
npm i -g vercel
vercel --prod
```

## 구조
- `index.html` — 메인 (WHY → CTA → Highlights → Work → About/이력서 오버레이)
- `project.html` — 프로젝트 상세 (`?p=vivizip|kb|musinsa|co-hi`)
- `public/support.js` — React 렌더 런타임
- `public/assets/` — 이미지 (히어로, 증명사진, 프로젝트 PNG)
