# [hairline](https://github.com/ufologist/hairline)

[![NPM version][npm-image]][npm-url] [![changelog][changelog-image]][changelog-url] [![license][license-image]][license-url]

[npm-image]: https://img.shields.io/npm/v/hairline.svg?style=flat-square
[npm-url]: https://npmjs.org/package/hairline
[license-image]: https://img.shields.io/github/license/ufologist/hairline.svg
[license-url]: https://github.com/ufologist/hairline/blob/master/LICENSE
[changelog-image]: https://img.shields.io/badge/CHANGE-LOG-blue.svg?style=flat-square
[changelog-url]: https://github.com/ufologist/hairline/blob/master/CHANGELOG.md

[![npm-image](https://nodei.co/npm/hairline.png?downloads=true&downloadRank=true&stars=true)](https://npmjs.com/package/hairline)

极细的线 - 用极简的方式实现 - [Demo](https://ufologist.github.io/hairline/test/index.html)

## Usage

### Usage1: npm

1. install

   ```
   npm install hairline --save
   ```
2. import
   
   ```javascript
   import 'hairline';
   ```
3. use

   ```html
   <div class="hairline hairline--round">hairline</div>
   ```

### Usage2: Download

1. download [`hairline.css`](https://unpkg.com/hairline)
2. link css

   ```html
   <link rel="stylesheet" href="path/to/hairline.css">
   ```
3. use

   ```html
   <div class="hairline hairline--round">hairline</div>
   ```

## APIDoc

| Class               | Description      |
|---------------------|------------------|
| `.hairline`         | base class |
| `.hairline--round`  | round hairline border      |
| `.hairline--top`    | top hairline border      |
| `.hairline--right`  | right hairline border      |
| `.hairline--bottom` | bottom hairline border      |
| `.hairline--left`   | left hairline border      |
| `.hairline--input`  | input/textarea element hairline border      |

## 其他实现

* [postcss-retina](https://github.com/Ziphwy/postcss-retina)
* [Hairlines · Framework7](https://framework7.io/docs/hairlines.html)
* [blear.scss.hairline](https://github.com/blearjs/blear.scss.hairline)
* [border-retina](https://github.com/AlanZou007/air-css/blob/master/src/mixins/border-retina.css)
* [border-1px.less](https://github.com/goddancer/npm/tree/master/border-1px.less)
* [border.less](https://github.com/yangyuji/border.less)
* [webkit-sassui-hairline](https://github.com/afeiship/webkit-sassui-hairline)
* [Hairline border](https://30-seconds.github.io/30-seconds-of-css/#hairline-border)
* [retina-border](https://github.com/wind-stone/retina-border)

## 参考

* [Retina屏的移动设备如何实现真正1px的线？](https://jinlong.github.io/2015/05/24/css-retina-hairlines/)
* [CSS retina hairline, the easy way](http://dieulot.net/css-retina-hairline)