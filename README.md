Udacity前端课程进阶P2“网站优化”项目
使用方法：点击dist/index.html 和dist/views/pizza.html 分别运行。
v0.0.1(2018/01/04)
·修改了index.html内的web字体代码，内置了style.css文档内容并且修改了css/print.css的媒体查询，使得PageSpeed分数提升至90分+
·优化了views/js/main.js，使得views/pizza.html在滚动时保持60fps的帧率
·优化了views/pizza.html，使得页面上的pizza尺寸滑块调整pizza大小的时间小于5毫秒
v0.0.2(2018/01/05)
·按照要求进一步压缩了views/images/pizzeria.jpg 至原来的18%大小（29K），使PageSpeed分数稳定90分+
·按照要求进一步优化了views/js/main.js 532行 i < 200 修改为 i < 100，设置了更合理的pizza数量，使页面更加流畅

代码分享地址：https://github.com/arrys1985/UdacityP2.git 版权为Udacity所有，本代码仅为在学期间作业