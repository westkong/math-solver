# 🧮 AI 수학 해설 생성기

> 수학 문제를 입력하거나 사진을 찍으면 단계별 풀이와 핵심 개념을 설명해주는 AI 튜터

**🔗 Demo:** https://westkong.github.io/math-solver/

---

## 📌 프로젝트 소개

고등학교 수학 강사로 재직하며 느낀 불편함에서 출발했습니다.  
반복되는 해설 작성을 AI로 자동화하고, 학생이 언제 어디서든 풀이를 확인할 수 있도록 만들었습니다.

---

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| 📝 텍스트 입력 | 수학 문제 직접 입력 후 AI 해설 생성 |
| 📷 사진 업로드 | 교재·시험지 사진 업로드 → Claude Vision으로 문제 인식 |
| 📋 클립보드 붙여넣기 | 캡처 화면 Ctrl+V로 바로 입력 |
| ➗ 수식 렌더링 | MathJax로 LaTeX 수식 실시간 렌더링 |
| ⚡ 스트리밍 응답 | 해설이 실시간으로 타이핑되며 출력 |
| 📚 과목 선택 | 수학Ⅰ·Ⅱ, 미적분, 확률과통계, 대수, 공통수학 |

---

## 🛠 기술 스택

- **Frontend:** HTML, CSS, Vanilla JavaScript (단일 파일)
- **AI:** Anthropic Claude API (`claude-sonnet-4-20250514`)
- **수식:** MathJax 3
- **배포:** GitHub Pages

---

## 🚀 사용 방법

1. [사이트](https://westkong.github.io/math-solver/) 접속
2. [Anthropic Console](https://console.anthropic.com)에서 발급한 API 키 입력
3. 과목 선택
4. 텍스트 입력 또는 사진 업로드
5. **해설 생성하기** 클릭

> API 키는 브라우저 내에서만 사용되며 외부 서버로 전송되지 않습니다.

---

## 💡 개발 배경

수학 강사로 고등학생 1학년, 2학년, 3학년 학생 10명에서 15명 정도를 지도하면서,  
같은 유형의 문제를 매번 손으로 해설하는 데 많은 시간이 소요됐습니다.  
Claude API의 Vision 기능과 스트리밍을 활용해  
**"문제 사진 한 장 → 즉시 단계별 해설"** 파이프라인을 구현했습니다.

---

## 📁 파일 구조

```
math-solver/
└── index.html   # 전체 소스 (HTML + CSS + JS 단일 파일)
```

---

## 👤 만든 사람

**westkong** · 가톨릭대학교 인공지능학과  
GitHub: [@westkong](https://github.com/westkong)
