# kimjihoon3106.github.io

Kim Ji Hoon의 개인 포트폴리오 페이지입니다.

## 로컬 실행

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 http://localhost:4000 으로 접속

## GitHub Pages 배포

1. GitHub에서 `kimjihoon3106.github.io` 이름으로 새 레포지토리 생성
2. 이 폴더를 해당 레포지토리에 push

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/kimjihoon3106/kimjihoon3106.github.io.git
git push -u origin main
```

3. GitHub 레포 Settings → Pages → Source: `main` 브랜치 선택 → Save

잠시 후 https://kimjihoon3106.github.io 에서 확인 가능

## 커스터마이즈

- `index.html` — About, Projects, Skills, Contact 내용 수정
- `assets/img/profile.jpg` — 프로필 사진 추가 후 index.html에서 img 태그 추가
- `_config.yml` — 사이트 제목, 이메일, GitHub 아이디 수정
