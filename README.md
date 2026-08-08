# Global Biotech Website

글로벌바이오테크 그룹 사이트 — 취급 8개 브랜드 통합 종합 홈페이지.
기존 chcrmkorea.com(Wix)를 대체하기 위한 신설 사이트.

## Stack
- 정적 HTML/CSS/JS (프레임워크 없음)
- Vercel Hobby 호스팅 · GitHub `main` push → 자동 배포
- Pretendard (한글) + Inter (영문)

## Structure (현재 · 첫 화면 초안)
- `index.html` — 홈 (Hero + 8 Brand Grid + CTA + Footer)
- `vercel.json` — cleanUrls, 보안 헤더, 이미지 캐시
- `robots.txt` · `sitemap.xml` — SEO 기본
- `images/` — 로고·브랜드 이미지 (추후 채움)

## Deployment
```
git add -A
git commit -m "설명"
git push
# → Vercel 자동 배포 3분
```
Live: https://globalbiotech-website.vercel.app

## Contact
- sales@chcrmkorea.com · Tel. 02-406-4387
- 글로벌바이오테크 · 660-30-00866 · 대표 정기운
- 경기도 성남시 중원구 갈마치로288번길 14, SK V1 Tower A동 1407호 (13215)
