# How to automation in selenium.  
1.Install `node.js`  
2.Run this npm command.  
`npm init -y`  
`npm install -D selenium-webdriver mocha chromedriver`  
3.Check chrome browser version.  
e.g., `95.0.4638.69`  
4.Record Selenium-IDE Tests.  
5.Export Selenium-IDE Tests for JavaScript.  
6.Write exported tests file in `./package.json`  
e.g.,  
```json
...
"scripts": {
    "test": "mocha ./hogehoge.spec.js"
  },
...
```
7.Download chromedriver.exe in this current-path.  
Note: Make sure the version of chromedrive.exe matches Chrome.  
URL: http://chromedriver.storage.googleapis.com/index.html  
  
8.Run npm test command.  
`npm run test`  
  
8.Finish.  
  