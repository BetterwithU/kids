# kids — 초등 수학 게임 모음

## 개요
초등 아이를 위한 수학 게임 모음. 현재: 네더 수학 디펜스 (소마셈 B2 연산 스피드 퀴즈).

## AI-Labs 허브 연동 (필수)
이 게임을 처음 배포하거나 아래 카드 정보(제목·설명·URL·태그)가 바뀌면:
→ `ai-labs` 레포의 `games.json`에 반영한다. (Claude가 push 시 먼저 상기)

### 허브 카드 정보 (games.json 원본)
- id:     `nether-math-defense`
- column: `future`
- tag:    초2 · 소마셈 B2 연산
- title:  🔥 네더 수학 디펜스
- desc:   마인크래프트 네더 세계에서 몰려오는 몹들의 수학 문제를 풀어 격파하는 스피드 연산 게임
- url:    https://BetterwithU.github.io/kids/nether_speedquiz/index.html
- cta:    게임 시작 →

## 구조
```
kids/
├── nether_speedquiz/   — 네더 수학 디펜스 게임 (index.html 단일 파일)
│   ├── mobs/           — 마인크래프트 몹 PNG
│   └── backgrounds/    — 네더 배경 PNG (10장)
└── IMG_*.jpg           — 소마셈 B2 문제집 사진 (문제 유형 참조용)
```

## 배포
GitHub Pages — https://BetterwithU.github.io/kids/nether_speedquiz/index.html
