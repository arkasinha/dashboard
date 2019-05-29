Create Project

npm init

npm i chai@4.1.2 chai-as-promised@7.1.1 chromedriver@2.41.0 faker@4.1.0 mocha@5.2.0 mochawesome@3.0.3 selenium-webdriver@4.0.0-alpha.1 --save-dev --unsafe-perm=true --allow-root

mocha test script: mocha test --reporter mochawesome --reporter-options autoOpen=true
Create directory and files

mkdir lib test utils

touch lib/basePage.js lib/homePage.js test/homePage.test.js utils/fakeData.js utils/locator.js

