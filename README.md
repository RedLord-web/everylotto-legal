# apps-legal

스튜디오 노트랩(Studio Knotlab)에서 운영하는 모바일 애플리케이션의 약관 및 개인정보처리방침 모음.

## URL

GitHub Pages: <https://redlord-web.github.io/apps-legal/>

## 구조

```
apps-legal/
├── index.html        ← 전체 앱 목록 (랜딩)
├── style.css         ← 공통 스타일
├── everylotto/       ← 모두의 로또 (한국, com.knotlab.everylotto)
│   ├── index.html
│   ├── privacy.html
│   └── terms.html
├── minanoloto/       ← みんなのロト / 모두의 로또 일본판 (com.knotlab.minanoloto)
│   ├── index.html
│   ├── privacy.html
│   └── terms.html
└── nihongo/          ← にほんGO / 일본어 학습 (com.knotlab.nihongo)
    ├── index.html
    ├── privacy.html
    └── terms.html
```

## 새 앱 추가

1. 새 폴더 생성 (영문 슬러그)
2. `index.html`, `privacy.html`, `terms.html` 작성 (기존 폴더 복사 후 수정)
3. 루트 `index.html`의 `app-grid`에 새 앱 카드 추가
4. 커밋 + 푸시 → GitHub Pages 자동 갱신

## 문의

knotlabdev@gmail.com
