---
title:  "github 블로그 chirpy 테마 적용"

categories: [github blog]
tags: [blog, chirpy]

date:   2024-09-03 14:01:31 +0900
---
chirpy Jekyll theme을 사용하기 위해 블로그들을 다 본 정리:<br>
Ruby 권장 버전 설치<br>
jekyll 설치<br>
bundler 설치<br>
repository 생성 (아이디.github.io)<br>
local에 clone<br>
jekyll new ./ (jekyll 사이트 생성)<br>
bundle install<br>
bundle update<br>
bundle install<br>
bundle exec jekyll serve<br>
bundle add webrick<br>
chirpy 테마 다운받아 압축 풀고 local repository에 덮어쓰기<br>
bash tools/init.sh 대신 수동 파일 삭제, 변경<br>
_config.yml 수정<br>
_post 폴더에 md 파일 포스팅<br>
git add, commit, push<br>
추가:<br>
겹치는 파일 chirpy 것 남기고 지움<br>
npm install && npm run build<br>
.gitignore에 _sass/dist, assets/js/dist 주석처리<br>
<br>
그래도 해결이 안 됐는데<br>
https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/_posts/2019-08-09-getting-started.md<br>
https://github.com/cotes2020/jekyll-theme-chirpy/wiki/Upgrade-Guide<br>
공식 튜토리얼을 따라하면 해결됐다.<br>
fork해서 만들고 mirror로 복제해 사용한다.