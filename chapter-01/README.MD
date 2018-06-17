## express cli basic structure
```ruby
express --ejs --css sass --git
```

## package.json add
+ 프로젝트에 관련된 정보를 추가하는 것은 좋은 습관이다.
```javascript
  "name": "chapter-01",
  "description": "Build a Twitter Like app using the MVC design pattern",
  "license": "MIT",
  "author": {
    "name": "Fernando Monteiro",
    "url": "https://github.com/newaeonweb/node-6-blueprints"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/newaeonweb/nodejs-6-blueprints.git"
  },
  "keywords": [
    "MVC",
    "Express Application",
    "Expressjs"
  ],
  "version": "0.0.1",
```

## app start
```ruby
DEBUG=chapter-01:* npm start
```