<h2 align="center"> <img src="preview/app_icon_title.png" width="340" /> </h2>

<p align="center">
	
<a href="https://www.google.com/search?q=web">
    <img src="https://img.shields.io/badge/Platform-Web-yellow.svg?color=purple"
      alt="Web" />
  </a>
	
<a href="https://angularjs.org">
    <img src="https://img.shields.io/badge/Framework-Angularjs-yellow.svg?color=red"
      alt="Framework" />
  </a>	
  	
  <a href="https://github.com/virtualvivek/ios-13-Calculators">
    <img src="https://img.shields.io/github/repo-size/vivekverma007/ios-13-Calculators.svg?color=orange"
      alt="Repo. Size" />
  </a>
  	<a href="https://github.com/virtualvivek/ios-13-Calculators/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/vivekverma007/ios-13-Calculators.svg?color=blue"
      alt="License: Apache" />
  </a>
  	<a href="https://github.com/virtualvivek/ios-13-Calculators">
    <img src="https://img.shields.io/badge/Release-v2.4-darklime.svg?style=flat"
      alt="Release" />
  </a>
  
  
  <a href="https://virtualizme-cals.netlify.com">
    <img src="https://img.shields.io/badge/⚡ live demo-here-green.svg?style=flat"
      alt="Demo" />
  </a>
  
  
</p>

<p align="center"><img src="preview/app_preview_main.jpg" width="740" /> </p> 


<h4 align="center">A light-weight library provides ios 13 style calculators for web applications</h4>

<p align="center">
<img src="preview/app_dark.png" width="28" />​ See a similar dark version  here - 
	<a href="https://github.com/virtualvivek/iwebCalculator">Dark version of ios Calculator</a>
</p>	

___

<p align="center">
	
<h3 align="center">Overview</h3>
 <p align="center">An ios 13 style calculators for web browsers.
 Easily Embbed and use calculated results easily in your pages. 
 This project is inspired from the <code>light theme</code> introduced by <i>apple inc.</i> to apply styles in <b>html css</b> format.</p>
 
</p>
 <p align="center">
 
 ## Installation
 
 Include `ios-calculators` folder in your target project file.
 
 Add where you want to add between your layout using a preprocessing language-

```php
<?php include 'include/Calculator.html';?>
```
#### OR  
Simply copy the html code and add between you page.


### Requirements

```html
<script type='text/javascript' src='angular.min.js'></script>

```
</p>  
​

## Basic Calculator

<img align="left" src="preview/anim_basic.gif" width="180" />

### Usage
To use values returned by the Basic calculator-
```html
use {{c_value}}

Eg: <input type="text" placeholder="Result" value="{{c_value}}"/>
```
OR through `ng` tag-
```js
ng-model="c_value"
```

​

​
## BMI Calculator

<img align="left" src="preview/anim_bmi.gif" width="180" />

### Usage
To use values returned by the BMI calculator-
```html
use {{b_value}}

Eg: <input type="text" placeholder="BMI value" value="{{b_value}}"/>
```
OR through `ng` tag-
```js
ng-model="b_value"
```


​
## Timer

<img align="left" src="preview/anim_timer.gif" width="180" />

### Usage

 <p><b>Standalone timer app here : </b><a href="app_Timer">ios-13-Calculators/iosTimer</a><p/>

To use values returned by the Timer-
```html
use {{counter | formatTimer}}

Eg:

<input type="text" placeholder="BMI value" value="{{counter | formatTimer}}"/>


```
​


​
​
​
​
​
​
​
​
​
## Grade Calculator

<img align="left" src="preview/app_index_Grade.PNG" width="180" />

### Usage
To use values returned by the Grade calculator-
```html
use id 'avg_grades'

Eg: <input type="text" id="avg_grades" placeholder="Grade" value="avg_grades"/>
```
OR through `assign` value-
```js
var value = document.getElementById("avg_grades").value;
```

​
​
## Macro Calculator

<img align="left" src="preview/app_index_Macro.PNG" width="180" />

### Usage
To use values returned by the Macro calculator-
```html
use class 'calories' using structure:

<h3 class="calories"><span>0</span> kcal</h3>
```
OR through `assign` value-
```js
var value = document.getElementById("calories").innerHtml;
```

<br><br><br>


### Browser Compatibility
![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)
--- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | 9.1+ ✔ | Latest ✔ |


## License

ios13-Calculators is licensed under `Apache-2.0 license`. View [license](https://github.com/virtualvivek/ios-13-Calculators/blob/master/LICENSE).<br>
Copyright (c) 2019-21 `Vivek Verma`
