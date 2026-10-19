# GPTers 디자인 시스템 페이지

정적 페이지(index.html + assets/). 배포: 공식 주소 https://gpters-design.vercel.app (프로젝트 geniefy/gpters-design). `.vercel` 링크는 gpters-design-system 프로젝트라 그냥 `vercel deploy --prod`하면 gpters-design-system.vercel.app에만 올라간다. 공식 주소는 `VERCEL_ORG_ID=team_8qkhcpmznw4QeEewUgrsupGF VERCEL_PROJECT_ID=prj_0tIk4P7bzBnxgRV3AftQ2YD0zaju npx vercel deploy --prod --yes`로 따로 올린다(10/19 확인).
- 원본 규칙: 마케팅 위키 `brand/design-system.md`, `brand/design-system-structure.md`, `brand/assets/components/banner-kit.css`
- 키트를 바꾸면 `assets/kit/banner-kit.css`도 위키 것으로 다시 복사한다.
- 폰트: Paperlogy(SIL OFL, Freesentation 공식), SUIT(SIL OFL, sun-typeface 공식 woff2), Clash Grotesk는 Fontshare CSS로만 불러온다(파일 재배포 금지).
- 지면별 배너 예시: `assets/kit/banner-slots.css`는 우리가 만든 파일(위키 정본 아님). `index.html`의 `#slots` 섹션과 `DESIGN.md` 5-1이 짝이다.
