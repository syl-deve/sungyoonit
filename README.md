# 성윤잇 (Sungyoonit) - Company Website

회사 공식 웹사이트입니다. GitHub Pages로 호스팅됩니다.

## 로컬에서 확인

그냥 브라우저에서 `index.html`을 여세요.

## 배포 방법

### 1. GitHub 저장소 생성

```bash
git init
git add .
git commit -m "Initial commit"
```

GitHub에서 `sungyoonit/sungyoonit.github.io` 저장소를 만든 후:

```bash
git remote add origin https://github.com/sungyoonit/sungyoonit.github.io.git
git push -u origin main
```

### 2. GitHub Pages 활성화

- 저장소 Settings → Pages → Branch: `main`, 폴더: `/ (root)` 선택
- 또는 `gh-pages` 브랜치로 푸시 후 해당 브랜치 선택

### 3. 커스텀 도메인 (선택)

- `CNAME` 파일에 도메인을 기록해두었습니다.
- GitHub Pages 설정에서 Custom domain 입력
- DNS 설정에서 `sungyoonit.com`의 CNAME 레코드를 `sungyoonit.github.io`로 연결

## 파일 구조

```
├── index.html        # 메인 랜딩 페이지
├── privacy.html      # 개인정보처리방침
├── css/
│   └── style.css     # 스타일시트
├── CNAME             # 커스텀 도메인 설정
└── README.md
```

## 내용 수정

- `index.html` - 회사 소개, 서비스, 연락처 정보 수정
- `privacy.html` - 개인정보처리방침 내용 수정
- `css/style.css` - 디자인 수정 (색상, 폰트 등)
