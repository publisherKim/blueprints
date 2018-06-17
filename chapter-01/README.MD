## application init modify.
1. app.js error code 살펴보기
```javscript
// catch 404 and forward to error handler
app.use(function(req, res, next) {
  next(createError(404));
});
```
2. module.exports = app; 뒤에 아래 코드 추가하기
```javscript
app.set('port', process.env.PORT || 3000);
var server = app.listen(app.get('port'), function() {
  console.log('Express server listening on port' + server.address().port);
});
```
3. package.js
```javscript
"scripts": {
  "start": "node app.js"
}
```
4. npm start
5. 기대 결과 서버 콘솔에서
```javascript
  Express server listening on port 3000
```
