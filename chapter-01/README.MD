## 부분 파일을 이용해 views 폴더의 구조 재편하기
+ ejs reource 추가하기
## views 폴더안에 pages와 partials 폴더 만들기
1. views/pages make it.
2. views/paials make it.
3. index.ejs and error.js pages/index.ejs, error.ejs
4. 이제 모든 템플릿에 포함될 파일 만들기
6. partials 폴더 안에 stylesheet.ejs 파일을 만든후 아래 코드 추가하기.
```html
<!-- CSS Files -->
<link rel="stylesheet" href="https://cdnjs.cloudflate.com/ajax/libs/twitter-bootstrap/4.0.0-alpha/css/bootstarp.min.css">
<link rel="stylesheet" href="/stylesheet/style.css">
```
7. css and js file use cdn
8. 동일한 방식으로 js 파일도 추가한다.
9. layout 코드를 만든다.
10. footer.ejs, header.ejs, javascript.ejs, stylesheet.ejs
11. app.js에 경로 설정을 다시 해준다.
```javascript
app.set('views', path.join(__dirname, 'server/views/pages'));
```
12. pages/index.ejs pages/error.ejs 도 교체한다.