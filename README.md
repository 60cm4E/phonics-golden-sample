# 🔤 진짜 쉬운 파닉스 (Phonics Golden Sample)

> 초등 4학년~중학 3학년 학생을 위한 영어 파닉스 학습 웹앱
> 「진짜 쉬운 파닉스는 이렇게 배웁니다」 책의 학습법을 디지털로 옮긴 골든샘플

## ✨ 학습 방식

알파벳 소리를 한 글자씩 분리해서 듣고 → 빠르게 합쳐서 단어로 읽는 방식.

```
ham = h /흐/ + a /애/ + m /음/
    = /흐애음/
    → 빠르게 읽어서 /햄/
```

## 📚 커리큘럼 (v8 · 골든샘플)

### 파닉스 본 학습 — 184 단어
- **Level 1: 단모음** (a / e / i / o / u) — 50 단어
- **Level 2: 매직 e** (a_e / e_e / i_e / o_e / u_e) — 24 단어
- **Level 3: 이중자음** (sh / ch / th / ph / wh / ng) — 30 단어
- **Level 4: 이중모음** (ai_ay / ee / ea / oa / ow / oi_oy) — 30 단어
- **Level 5: 사이트워드** (1~5군) — 50 단어

### 짧은 독해 — 12 지문 (Module C, NEW v8)
- Level 1 단모음 5개 지문 (a/e/i/o/u 각 1개)
- Level 2 매직 e 2개 지문
- Level 3 이중자음 2개 지문
- Level 4 이중모음 2개 지문
- Level 5 사이트워드 1개 지문
- 전체 듣기 / 문장별 듣기 / 한글 토글 / "다 읽었어요" 진도

### EGU 어휘 — 4 테마 × 5단어 = 20단어 (Module D, NEW v8)
- 🏠 집 (door, window, bed, chair, clock)
- 👨‍👩‍👧‍👦 가족 (mom, dad, baby, sister, brother)
- 🏫 학교 (book, pen, desk, bag, pencil)
- 🍔 음식 (rice, bread, milk, apple, cake)
- 단어별 발음 듣기 + 학습 완료 체크

## 🛠️ 사용 방법

별도 빌드 없음. `index.html`을 브라우저로 더블클릭하면 실행됩니다.
온라인: <https://phonics-golden-sample.vercel.app/>

## 🔧 기술 스택

- React 18 (CDN)
- Tailwind CSS (CDN)
- Babel Standalone (JSX 트랜스파일)
- Web Speech API (TTS)
- localStorage (진도 저장)
- 자체 인라인 SVG 일러스트 약 150개 + 이모지 폴백

## 📝 주요 기능

- 단어 학습: 분리 듣기(느림) → 합쳐 듣기(빠름)
- 입 모양 가이드 (모음별)
- 4지선다 그림 매칭 퀴즈
- 단계별 진도 추적 (localStorage)
- ⚠️ 학생 직접 이미지 오류 신고 버튼
- 📊 학습 통계 대시보드 (7일 그래프 · Level별 진도)
- 📖 짧은 독해 (전체 듣기 / 문장별 듣기 / 한글 토글)
- 📚 EGU 어휘 (4 테마, 발음 + 학습 체크)

## 🤝 자료 출처

- 「진짜 쉬운 파닉스는 이렇게 배웁니다」 (책)
- 「저절로 리딩 STARTER Level 1」 (보조 교재)
- 「EGU 영단어 & 품사」 (보조 교재)

일러스트는 모두 자체 제작 SVG (책 그림 사용 X)이며, 학습 단어 리스트는 일반 파닉스 표준 + 책의 단어를 참고했습니다.

## 📄 라이선스

학습 목적 비영리 사용 가능.
