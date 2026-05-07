# ReturnRx PWA — 설치 가이드

## 📁 파일 구성
```
returnrx-pwa/
├── index.html       ← 앱 본체
├── manifest.json    ← PWA 설정
├── sw.js            ← 오프라인 캐시
├── icon-192.png     ← 앱 아이콘
└── icon-512.png     ← 앱 아이콘 (대형)
```

---

## 🚀 배포 방법 (GitHub Pages — 무료)

### 1단계: GitHub 계정 만들기
https://github.com 에서 가입

### 2단계: 새 저장소(Repository) 만들기
- 우측 상단 + → "New repository"
- Repository name: `returnrx` (소문자)
- Public 선택
- "Create repository" 클릭

### 3단계: 파일 올리기
- "uploading an existing file" 클릭
- 위 5개 파일을 모두 드래그 앤 드롭
- "Commit changes" 클릭

### 4단계: GitHub Pages 활성화
- 저장소 → Settings → Pages
- Source: "Deploy from a branch"
- Branch: main / (root)
- Save

### 5단계: 앱 주소 확인
약 1~2분 후 아래 주소로 접속 가능:
```
https://[내 GitHub 아이디].github.io/returnrx/
```

---

## 📱 안드로이드에서 앱 설치하기

1. Chrome으로 위 주소 접속
2. 주소창 오른쪽 점 3개 메뉴 탭
3. **"앱 설치"** 또는 **"홈 화면에 추가"** 선택
4. "설치" 확인

→ 홈 화면에 **ReturnRx 아이콘**이 생깁니다 🎉

---

## ✅ PWA 특징
- 인터넷 없어도 앱 실행 가능 (오프라인)
- 데이터는 폰 로컬에 저장 (개인정보 안전)
- AI 기능(계수기)은 인터넷 연결 필요
- 업데이트: 파일만 다시 올리면 자동 반영
