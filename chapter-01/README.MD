## application structure change.
1. 프로젝트 폴더 안에 다음 폴더를 만든다.
+ server
2. server 폴더 안에 다음 폴더들을 만든다.
+ config
+ routes
+ views
3. config폴더에 포함될 내용은 나중에 만든다.
4. chapter-01/views/error.js와 index.js chapter-01/server/views 폴더로 이동
5. chapter-01/routes index.js와 user.js 파일을 chapter-01/server/routes 폴더로 이동
6. path가 바꼈으니 app.js 경로를 수정한다.
```ruby
DEBUG=chapter-01:* npm start
```
7. 빈 폴더를 삭제한다.(routes, views)