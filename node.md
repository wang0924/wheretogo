一个vue文件就是一个组件其中包括使用template定义的模板，使用script定义的js文件和style样式文件，需要通过export default 向外暴露组件，如果需要使用通过import from引入即可



1.初始化项目在main.html文件中引入reset.css文件进行样式的初始化

2.引入border.css解决移动端1像素边框问题，由于又得手机分辨率比较高导致是二倍屏和三倍屏，当写1px soild 显示的不是1像素而是两像素和三像素

3.引入fastclick第三方库来解决移动端click事件点击后延时300ms问题 npm i fastclick -S

4.在iconfont创建项目

5.npm i stylus -S  npm i stylus-loader安装组件，方便css开发  

6.在home下创建components文件夹存放组件

7.在styles文件夹下存放iconfont字体图标，在定义varribles.styl文件来存放公共的样式，定义变量存放样式，在通过@import引入样式文件就可以使用了

8.在build文件夹下的webpack.base.conf.js文件自己定义一个别名来代替style所在路径，类似于@符代表src所在的路径 修改后需要重启服务器

9.git add . git commit -m '' git push