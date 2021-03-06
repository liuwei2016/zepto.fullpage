zepto.fullpage [![release](https://img.shields.io/badge/release-v0.3.1-orange.svg)](https://github.com/yanhaijing/zepto.fullpage/releases/tag/v0.3.1) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yanhaijing/zepto.fullpage/blob/master/MIT-LICENSE.txt)
==============

专注于移动端的fullPage.js，依赖Zepto。

## 功能概述
可实现移动端的单页滚动效果，可自定义参数，提供回调接口，和公开接口。

## 兼容性

- Ios4+
- Andriod2.3+（未全部覆盖）

## 快速上手
### HTML

	<div class="wp">
        <div class="wp-inner">
            <div class="page page1">1</div>
            <div class="page page2">2</div>
            <div class="page page3">3</div>
            <div class="page page4">4</div>
        </div>
    </div>

### CSS
父容器需是固定高度，并且溢出为隐藏，fullpage会使用父元素的宽度和高度。

	.wp{
	    overflow: hidden;            
	}

## js
一行代码即可完成，如此简单：

	$('.wp-inner').fullpage();

**注意：是在.wp-inner上调用的。**

更多例子，请移步[这里](demo)。

## 文档

[API](doc/api.md)

## 贡献指南

如果你想为zepto.fullpage贡献代码，请采用fork + pull request 方式，并在发起pr前先将master上超前的代码rebase到自己的分支上。

### 发布Bower
    
    $ bower register zepto.fullpage git://github.com/yanhaijing/zepto.fullpage.git

## 报告问题

- [Issues](https://github.com/yanhaijing/zepto.fullpage/issues "报告问题")

## 贡献者

**yanhaijing**

- [Weibo](http://weibo.com/yanhaijing1234 "yanhaijing's Weibo")
- [Email](mailto:yanhaijing@yeah.net "yanhaijing's Email")
- [Blog](http://yanhaijing.com "yanhaijing's Blog")

**YuyingWu**
- [Blog](http://blog.wuyuying.com/)

## 为什么会有这个项目
最近单页滚动的效果非常流行，这种效果的视觉冲击感很强烈，特别是对于活动页面，因为需求的迫切，在pc端诞生了 fullPage.js和onepage-scroll这样的库，在移动的浪潮下，我们自然需要把这种效果搬到移动设备上，但当我在想实现类似效果时，却找不到一个这样的库（fullpage.js对于移动端来说太大了，还要依赖jquery），所以我就开发了一个，先是用于自己项目中，后来抽了出来，就有了这个项目。

## 更新日志

[更新日志](CHANGELOG.md)

## TODO
- 横向滚屏 v0.3.0 [√]
- 循环滚动 v0.2.0 [√]

## 谁在使用
**注:如果您也在使用，欢迎[反馈给我](https://github.com/yanhaijing/zepto.fullpage/issues/9)**

- [百度知道](http://zhidao.baidu.com/)
- [百度经验](http://jingyan.baidu.com/)

## 成功案例
- [百度知道-APP5.0落地页](http://zhidao.baidu.com/s/5_0-page/index.html)
- [重庆华西妇产医院-妈妈我来啦](http://d.cqhxfk.com/game/0505/)
- [百度经验-关于表白这事儿](http://jingyan.baidu.com/z/2015-520/index.html)

## 相关链接
- [fullPage.js](https://github.com/alvarotrigo/fullPage.js)
- [onepage-scroll](https://github.com/peachananr/onepage-scroll)
- [zepto-onepage-scroll](https://github.com/peachananr/zepto-onepage-scroll)
- [parallax.js](https://github.com/hahnzhu/parallax.js)
- [H5FullscreenPage](https://github.com/lvming6816077/H5FullscreenPage)
