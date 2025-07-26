# RonyKorea - iOS 앱 개발자 포트폴리오

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://ronykorea.github.io)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

혁신적인 iOS 앱을 개발하는 RonyKorea의 개인 포트폴리오 웹사이트입니다. GitHub Pages를 이용해 배포되며, 반응형 디자인으로 모든 디바이스에서 최적화된 경험을 제공합니다.

## 🌐 라이브 데모

**[ronykorea.github.io](https://ronykorea.github.io)** 에서 실시간으로 확인하실 수 있습니다.

## ✨ 주요 기능

### 📱 완전 반응형 디자인
- 모바일, 태블릿, 데스크톱 모든 화면 크기에 최적화
- 터치 친화적인 모바일 네비게이션
- 성능 최적화된 CSS Grid 및 Flexbox 레이아웃

### 🎨 현대적인 UI/UX
- 최신 iOS 디자인 언어를 반영한 인터페이스
- 부드러운 애니메이션 및 트랜지션 효과
- 접근성을 고려한 색상 대비 및 폰트 크기

### 🚀 고성능 웹사이트
- Vanilla JavaScript로 구현된 가벼운 코드
- 지연 로딩(Lazy Loading) 및 이미지 최적화
- 60fps 부드러운 스크롤 애니메이션

### 📊 인터랙티브 요소
- 실시간 통계 카운터 애니메이션
- 스크롤 기반 콘텐츠 페이드인 효과
- 다이나믹한 타이핑 애니메이션

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Fonts**: Google Fonts (Inter)
- **Icons**: Font Awesome 6.4.0
- **Hosting**: GitHub Pages
- **Version Control**: Git

## 📁 프로젝트 구조

```
myhome/
├── index.html          # 메인 HTML 파일
├── style.css           # 메인 스타일시트
├── script.js           # JavaScript 기능
├── README.md           # 프로젝트 문서
└── myhome.code-workspace  # VS Code 워크스페이스 설정
```

## 🚀 GitHub Pages 배포 방법

### 1. 저장소 설정

1. GitHub에서 새 저장소를 생성합니다.
   - 저장소 이름: `ronykorea.github.io` (본인의 GitHub 사용자명을 사용)
   - Public 저장소로 설정

2. 로컬에서 저장소를 클론합니다:
   ```bash
   git clone https://github.com/ronykorea/ronykorea.github.io.git
   cd ronykorea.github.io
   ```

### 2. 파일 업로드

1. 프로젝트 파일들을 저장소 루트에 복사합니다:
   ```bash
   cp index.html style.css script.js README.md ./
   ```

2. Git에 추가하고 커밋합니다:
   ```bash
   git add .
   git commit -m "Initial commit: Add iOS app portfolio website"
   git push origin main
   ```

### 3. GitHub Pages 활성화

1. GitHub 저장소 페이지로 이동
2. `Settings` 탭 클릭
3. 왼쪽 메뉴에서 `Pages` 선택
4. Source를 `Deploy from a branch` 선택
5. Branch를 `main` 선택
6. `Save` 클릭

### 4. 접속 확인

약 5-10분 후 `https://ronykorea.github.io`에서 웹사이트를 확인할 수 있습니다.

## 🎨 커스터마이징 가이드

### 개인 정보 수정

**index.html에서 수정할 내용:**
- 이름, 제목, 소개 텍스트
- 앱 정보 (이름, 설명, 아이콘)
- 연락처 정보
- 소셜 미디어 링크

**style.css에서 수정할 내용:**
- 색상 팔레트 (CSS 변수 사용 권장)
- 폰트 및 타이포그래피
- 레이아웃 및 간격

### 앱 추가/수정

`index.html`의 앱 섹션에서 새로운 앱 카드를 추가하거나 기존 정보를 수정할 수 있습니다:

```html
<div class="app-card">
    <div class="app-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3 class="app-title">Your App Name</h3>
    <p class="app-description">앱 설명</p>
    <div class="app-features">
        <span class="feature-tag">기능1</span>
        <span class="feature-tag">기능2</span>
    </div>
    <div class="app-links">
        <a href="APP_STORE_LINK" class="app-store-btn">
            <i class="fab fa-apple"></i>
            App Store
        </a>
    </div>
</div>
```

## 📱 섹션 설명

### 🏠 홈 (Hero Section)
- 임팩트 있는 첫인상
- 타이핑 애니메이션으로 주목도 증가
- CTA 버튼으로 사용자 액션 유도

### 📱 앱 소개 (Apps Section)
- 개발한 iOS 앱들의 카드형 레이아웃
- 각 앱의 주요 기능 및 App Store 링크
- 호버 효과로 인터랙티브함 증대

### ⭐ 특징 (Features Section)
- 개발자로서의 강점과 차별점
- 아이콘과 함께 시각적으로 표현
- 4개의 핵심 가치 제시

### 👨‍💻 소개 (About Section)
- 개발자 개인 소개
- 기술 스택 및 경험
- 성과 통계 (애니메이션 포함)

### 📧 연락처 (Contact Section)
- 다양한 연락 방법 제시
- 실시간 폼 검증 기능
- 깔끔한 2단 레이아웃

## 🔧 추가 기능 구현 아이디어

### 🌙 다크 모드
```javascript
// script.js에 이미 기본 구조가 포함되어 있습니다
function toggleTheme() {
    document.body.classList.toggle('dark-theme');
}
```

### 📊 Google Analytics 연동
```html
<!-- index.html head 섹션에 추가 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
```

### 🎯 실제 Contact Form 연동
```javascript
// Netlify Forms, Formspree, 또는 EmailJS 사용
// script.js의 contact form handler 수정
```

## 🐛 알려진 이슈 및 해결방법

### iOS Safari에서 vh 단위 문제
```css
/* 모바일 Safari의 주소창 때문에 발생하는 문제 해결 */
.hero {
    min-height: 100vh;
    min-height: -webkit-fill-available;
}
```

### 폰트 로딩 최적화
```html
<!-- 폰트 preload 추가 -->
<link rel="preload" href="font-url" as="font" type="font/woff2" crossorigin>
```

## 📈 성능 최적화

- ✅ 압축된 이미지 사용 (WebP 권장)
- ✅ CSS/JS 미니파이
- ✅ CDN을 통한 라이브러리 로드
- ✅ 지연 로딩 구현
- ✅ 캐싱 최적화

## 🤝 기여하기

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 라이선스

이 프로젝트는 MIT 라이선스로 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 📞 연락처

- **Email**: contact@ronykorea.com
- **GitHub**: [@ronykorea](https://github.com/ronykorea)
- **Website**: [ronykorea.github.io](https://ronykorea.github.io)

---

⭐ 이 프로젝트가 도움이 되었다면 스타를 눌러주세요! 