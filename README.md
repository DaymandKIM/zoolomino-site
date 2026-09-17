# zoolomino-site

Zoolomino 의 공개 지원 페이지. GitHub Pages 로 호스팅한다.
스토어의 **Support URL** 이 여기를 가리킨다 — 심사자가 실제로 연다.

- `index.html` — 지원 페이지. 앱 기본 언어가 영어라 영어가 먼저고 한국어가 아래에 있다.
- `privacy.html` — **방침이 아니라 리다이렉트다.** 아래 참고.

## 개인정보처리방침은 여기 없다

2026-09-15 에 회사 사이트로 옮겼다.

```
https://daylongs.com/policies/zoolomino/privacy
```

원본은 `daylongs` 저장소의 `public/policies/zoolomino/privacy.html` 하나뿐이다.

**여기에 사본을 다시 두지 말 것.** 사본이 둘이면 반드시 어긋나고, 그때 스토어가
여는 쪽은 항상 옛것이다. 실제로 그렇게 됐었다 — 이 저장소의 `privacy.html` 이
2026-08-27 자인 채로 남아 사업자 정보가 없는 방침을 공개하고 있었고, 그동안 앱
안 방침과 회사 사이트 방침만 갱신됐다. 같은 앱의 공개 방침이 둘이 되어 서로
다른 말을 하고 있었다.

`privacy.html` 은 지우지 않고 정식 주소로 넘기게 두었다. 지우면 예전에 이 주소를
본 사람과 검색 결과가 404 를 만난다.

## 배포

저장소 Settings → Pages → Source 를 `main` 브랜치 `/ (root)` 로 두면 끝.

## 주의

- 이 저장소는 **공개**여야 한다. GitHub Pages 는 비공개 저장소에서 유료 플랜이 필요하다.
- 앱 소스는 별도의 비공개 저장소(`zoolomino`)에 둔다.
- 앱 안 방침(`App.jsx` 의 `PRIVACY`, 40개 언어)을 고치면 `daylongs` 쪽 방침도
  같이 고쳐야 한다. 두 곳이 어긋나면 심사에서 문제가 된다.
