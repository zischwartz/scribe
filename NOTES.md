STEPS
bower install

cd src
node r.js -o app.build.js

node r.js -o baseUrl=. name=almond.js include=scribe.js out=main-build.js
