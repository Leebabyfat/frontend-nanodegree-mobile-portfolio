## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html
1.首先将本地服务器tomcat打开
2.通过loclahost:8080/frontend-nanodegree-mobile-portfolio来访问index.html
3.打开Google开发者工具检查，点击Pagespeed查看网页得分
4.根据PageSpeed提示进行了压缩图片，下载了已经压缩好的图片替换掉原图片，修改了图片的尺寸。
5.清除浏览器缓存后，重新进行pagespeed分析，得分为95/100。

#### Part 2: Optimize Frames per Second in pizza.html
1.首先将本地服务器tomcat打开
2.通过loclahost:8080/frontend-nanodegree-mobile-portfolio/views/pizza.html来访问pizza.html
3.对pizza.html和main.js进行压缩

You might find the FPS Counter/HUD Display useful in Chrome developer tools described here: [Chrome Dev Tools tips-and-tricks](https://developer.chrome.com/devtools/docs/tips-and-tricks).