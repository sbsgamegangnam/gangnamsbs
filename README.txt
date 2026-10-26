SBS아카데미게임학원 강남점 홈페이지 (정적 사이트)

[배포] GitHub 업로드 → Netlify에서 Import from Git → gangnamsbs 저장소 → Deploy (빌드 설정 비움)
사이트 주소 기준: https://gangnamsbs.netlify.app  ※ 다른 주소로 배포하면 sitemap.xml·robots.txt·각 페이지 canonical을 다시 생성해야 합니다.

[주소 구조]
/                         홈
/courses/ /support/ /campus/ /news/ /consult/ /about/
/blog/ + 글 5편
지역·과목 페이지 8개: gangnam-game, gangnam-wonhwa, gangnam-webtoon, gangnam-webnovel, gangnam-coding, gangnam-planning, sinnonhyeon-game, seocho-game

[파일]
assets/app.js  내용·동작 (BRANCH 지점정보, BOOK 예약, posts 글, localGuides 지역 페이지)
assets/site.css 스타일 (맨 아래 '강남점 추가' 블록)
각 폴더 index.html은 검색엔진용으로 미리 그려 둔 페이지입니다.
