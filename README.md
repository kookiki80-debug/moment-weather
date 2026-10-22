# 모멘트 · Moment

계산기와 실시간 날씨를 제공하는 작은 생산성 앱입니다.

## 기능

- 키보드 입력을 지원하는 계산기
- Open-Meteo 기반 현재 날씨: 지역 선택, 현재 위치, 10분마다 갱신
- 25분·50분 집중 타이머와 5분 휴식 타이머
- 브라우저에 자동 저장되는 메모
- 모바일 대응 화면

## 실행

`index.html`을 브라우저로 열거나 GitHub Pages 배포 주소에 접속하세요.
날씨와 웹 폰트를 불러오려면 인터넷 연결이 필요합니다.
현재 위치 조회에는 브라우저의 위치 권한이 필요하며, HTTPS 환경에서 사용하는 것을 권장합니다.
메모는 사용하는 브라우저에만 저장되며 GitHub에는 전송되지 않습니다.

## 배포

GitHub Pages의 **Deploy from a branch**에서 `main` 브랜치의 `/ (root)`를 선택합니다.
이후 `main`에 변경 사항을 푸시하면 자동으로 다시 배포됩니다.

## 변경 사항 올리기

```sh
git add index.html
git commit -m "Update productivity app"
git push
```

날씨 데이터: [Open-Meteo](https://open-meteo.com/)
