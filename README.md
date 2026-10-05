# 권유현 Portfolio

웹·앱 개발자 권유현의 포트폴리오 사이트입니다.

## 배포 (GitHub Pages)

1. GitHub에 `develop-kwon.github.io` 이름으로 저장소를 만든다.
2. 이 저장소를 push 한다.
   ```bash
   git remote add origin https://github.com/develop-kwon/develop-kwon.github.io.git
   git push -u origin main
   ```
3. 저장소 **Settings → Pages → Build and deployment**에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 지정한다.
4. 몇 분 뒤 https://develop-kwon.github.io 에서 확인한다.

빌드 과정 없이 `index.html`을 그대로 서비스하며, `.nojekyll`로 Jekyll 처리를 끈다.

## 구조

```
index.html        페이지 본문
assets/           템플릿 CSS·JS·폰트 (HTML5 UP 원본)
images/           프로필 사진, 프로젝트 이미지
LICENSE.txt       템플릿 라이선스 (CCA 3.0)
```

## Credits

Design: [Read Only](https://html5up.net/read-only) by HTML5 UP (CCA 3.0 — 푸터의 크레딧은 유지해야 한다).
