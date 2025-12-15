# 📄 Markdown Viewer

**브라우저에서 마크다운 파일을 아름답게 보여주는 뷰어 앱**

마크다운 파일을 드래그 앤 드롭하거나 선택하면, GitHub 스타일의 깔끔한 디자인으로 렌더링해주는 웹 애플리케이션입니다.

![Markdown Viewer](https://img.shields.io/badge/Markdown-Viewer-00f2ff?style=for-the-badge&logo=markdown&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

🔗 **[Live Demo](https://jvibeschool.org/MDVIEW/)** | 라이브 데모에서 직접 체험해보세요!

---

## ✨ 주요 기능

### 🎨 4가지 테마 지원
- **다크 테마** - GitHub 스타일의 어두운 테마 (기본값)
- **라이트 테마** - 밝고 깔끔한 화이트 테마
- **그레이 테마** - 눈의 피로를 줄이는 중간 톤 테마
- **모노 테마** - 프린트에 최적화된 흑백 테마

### 📝 마크다운 렌더링
- **완전한 마크다운 지원** - 모든 마크다운 문법 지원
- **구문 강조** - highlight.js를 활용한 코드 블록 하이라이팅
- **테이블 스타일링** - 아름답게 스타일링된 테이블
- **이모지 지원** - 모든 이모지 정상 표시
- **뱃지 한 줄 표시** - 기술 스택 뱃지들을 한 줄로 깔끔하게 정렬

### 🖱️ 사용자 친화적 인터페이스
- **드래그 앤 드롭** - 파일을 드래그해서 바로 업로드
- **파일 선택** - 클릭하여 파일 선택 가능
- **통계 표시** - 글자 수, 단어 수, 줄 수 실시간 표시
- **테마 자동 저장** - 선택한 테마가 자동으로 저장되어 다음 방문 시 유지

### 🖨️ 인쇄 기능
- **프린트 최적화** - 모노 테마는 프린트에 최적화
- **깔끔한 출력** - 헤더/툴바 자동 숨김
- **키보드 단축키** - `Ctrl+P` (또는 `Cmd+P`)로 빠른 인쇄

### 📱 반응형 디자인
- **모바일 지원** - 스마트폰에서도 완벽하게 작동
- **태블릿 최적화** - 태블릿 화면에 최적화된 레이아웃
- **데스크톱 최적화** - 넓은 화면에서 최대한 활용

---

## 🚀 시작하기

### 설치
별도의 설치 과정 없이 바로 사용 가능합니다.

```bash
# 프로젝트 클론 (또는 파일 다운로드)
git clone https://github.com/your-repo/markdown-viewer.git

# 폴더 이동
cd markdown-viewer

# 브라우저에서 열기
open index.html  # macOS
# 또는
start index.html  # Windows
# 또는
xdg-open index.html  # Linux
```

### 로컬 서버 실행 (권장)
일부 기능(데모 버튼 등)은 로컬 서버에서만 작동합니다.

```bash
# Python 3
python3 -m http.server 8080

# Node.js (http-server 설치 필요)
npx http-server -p 8080

# PHP
php -S localhost:8080
```

그 후 브라우저에서 `http://localhost:8080` 접속

---

## 📖 사용법

### 1. 파일 업로드
- **드래그 앤 드롭**: 마크다운 파일을 업로드 영역에 드래그
- **파일 선택**: 업로드 영역 클릭하여 파일 선택
- **지원 형식**: `.md`, `.markdown`, `.txt`

### 2. 테마 변경
1. 헤더 우측 상단의 테마 버튼 클릭
2. 원하는 테마 선택 (다크/라이트/그레이/모노)
3. 테마가 자동으로 저장되어 다음 방문 시 유지

### 3. 파일 통계 확인
- 업로드된 파일의 통계가 툴바에 표시됩니다:
  - **글자 수**: 전체 문자 수
  - **단어 수**: 공백으로 구분된 단어 수
  - **줄 수**: 전체 줄 수

### 4. 인쇄
- **인쇄 버튼**: 툴바의 인쇄 버튼 클릭
- **키보드 단축키**: `Ctrl+P` (Windows/Linux) 또는 `Cmd+P` (macOS)

### 5. 새 파일 열기
- **새 파일 버튼**: 툴바의 "새 파일" 버튼 클릭
- **키보드 단축키**: `Ctrl+O` (Windows/Linux) 또는 `Cmd+O` (macOS)

---

## 🎨 테마 상세

### 다크 테마
- **배경**: 어두운 회색 (#0d1117)
- **텍스트**: 밝은 회색 (#e6edf3)
- **액센트**: 밝은 파란색 (#58a6ff)
- **용도**: 일반적인 다크 모드 사용

### 라이트 테마
- **배경**: 흰색 (#ffffff)
- **텍스트**: 어두운 회색 (#1f2328)
- **액센트**: 파란색 (#0969da)
- **용도**: 밝은 환경에서 사용

### 그레이 테마
- **배경**: 중간 회색 (#232323)
- **텍스트**: 밝은 회색 (#e8e8e8)
- **액센트**: 하늘색 (#5dade2)
- **용도**: 눈의 피로 감소, 중간 톤 선호

### 모노 테마
- **배경**: 흰색 (#ffffff)
- **텍스트**: 검은색 (#000000)
- **액센트**: 검은색 (#000000)
- **용도**: 프린트, 흑백 출력 최적화

---

## 📂 파일 구조

```
markdown-viewer/
├── index.html      # 메인 HTML 파일 (모든 기능 포함)
└── README.md       # 프로젝트 문서
```

**단일 파일 구조**: 모든 CSS와 JavaScript가 `index.html`에 포함되어 있어 별도의 파일 없이 바로 사용 가능합니다.

---

## 🛠️ 기술 스택

- **HTML5** - 구조
- **CSS3** - 스타일링 (CSS Variables, Flexbox, Grid)
- **JavaScript (ES6+)** - 로직
- **marked.js** - 마크다운 파싱
- **highlight.js** - 코드 구문 강조
- **LocalStorage** - 테마 설정 저장

---

## ⌨️ 키보드 단축키

| 단축키 | 기능 |
|--------|------|
| `Ctrl/Cmd + P` | 인쇄 |
| `Ctrl/Cmd + O` | 새 파일 열기 |

---

## 🌐 브라우저 지원

| 브라우저 | 지원 버전 |
|---------|----------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |

---

## 🎯 주요 특징

### 코드 블록
- **구문 강조**: 100개 이상의 프로그래밍 언어 지원
- **macOS 스타일**: 코드 블록 상단에 창 버튼 디자인
- **테마별 하이라이팅**: 선택한 테마에 맞는 코드 하이라이팅

### 테이블
- **호버 효과**: 마우스 오버 시 행 하이라이트
- **깔끔한 스타일**: 헤더와 본문 구분
- **반응형**: 작은 화면에서도 스크롤 가능

### 링크
- **호버 효과**: 마우스 오버 시 밑줄 표시
- **액센트 컬러**: 테마에 맞는 링크 색상

---

## 📝 마크다운 지원 기능

✅ **헤딩** (H1~H6)  
✅ **강조** (Bold, Italic)  
✅ **링크**  
✅ **이미지**  
✅ **코드 블록** (구문 강조 포함)  
✅ **인라인 코드**  
✅ **리스트** (순서 있는/없는)  
✅ **테이블**  
✅ **인용구**  
✅ **수평선**  
✅ **체크박스**  
✅ **이모지**  
✅ **뱃지** (한 줄 정렬)

---

## 🔧 커스터마이징

### 테마 색상 변경
`index.html` 파일의 CSS 변수를 수정하여 테마 색상을 변경할 수 있습니다:

```css
:root {
    --bg-primary: #0d1117;
    --text-primary: #e6edf3;
    --accent-cyan: #58a6ff;
    /* ... 기타 변수들 */
}
```

### 코드 하이라이팅 테마 변경
highlight.js 테마를 변경하려면 CDN 링크를 수정하세요:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/[테마명].min.css">
```

---

## 📄 라이선스

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

---

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📞 문의

프로젝트에 대한 문의사항이나 제안이 있으시면 Issue를 생성해주세요.

---

## 🎉 업데이트 내역

### v1.0.0 (2026)
- ✨ 4가지 테마 지원 (다크, 라이트, 그레이, 모노)
- ✨ 드래그 앤 드롭 파일 업로드
- ✨ 코드 구문 강조
- ✨ 파일 통계 표시
- ✨ 테마 자동 저장
- ✨ 인쇄 기능
- ✨ 반응형 디자인
- ✨ 뱃지 한 줄 정렬

---

<p align="center">
  <b>📄 마크다운 파일을 아름답게 보여주세요!</b>
</p>

