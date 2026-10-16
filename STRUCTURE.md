# STRUCTURE · tir-sample

```
tir-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = tir-sample → tir-sample.lgt3232.workers.dev
├─ .assetsignore           img/·문서·index_*.html·미사용 webp 3장 배포 제외
├─ tr-grotesk.woff2        제목 (Space Grotesk 300–700)
├─ tr-mono.woff2           캡션·라벨 (Space Mono)
├─ tr-pretendard.woff2     한글 (사용 글자만 → 글자 추가 시 재생성)
├─ tr-logo-ink.png         로고 먹색 (헤더)
├─ tr-logo-yellow.png      로고 노랑 (히어로 장식 · 푸터)
├─ tr-*.webp               사진 (window·room·cup = 히어로 크로스페이드)
├─ favicon.png / og-tiir.jpg
├─ img/                    다올 제공 원본 39장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(`#slides` + 작품 라벨 `.label`) → Statement(벽) → `#collection`(작품 8 + 메뉴 분류) → `#room`(벽 · 6) → `#pets`(노랑 띠) → `#visit` → 먹색 푸터.

## 작품 캡션 수정
`<figcaption><span class="no">No. 01</span><b>제목</b>재료, 재료</figcaption>`. 메뉴판을 받으면 제목을 실제 메뉴명 + 가격으로 바꾸면 됨.

## 색 규칙
노랑 `--yellow`은 글자색 금지(형광펜 `.hl` · 면 · 호버만). 코발트 `--cobalt`은 작은 표시와 호버.
