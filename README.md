### Vidage.js
###### Your solution to Background Video & Image
---

**Vidage.js** will automatically hide and pause the video for touch devices and/or small screens (34em) and instead show the fallback image. It determines whether to do that or not, on the `canplay`, `resize` and `orientationchange` _(probably not necessery)_ events. It uses one module as dependency - `lodash/debounce`.

#### Demo
Take a look at this simple, yet - [beautiful example](https://dvlden.github.io/Vidage.js/).

#### Bower
`bower install vidage --save`

#### NPM
`npm install vidage --save`

#### How to use it
You may use Vidage on one of the following ways:

##### Regular way
```html
&lt;script src="scripts/Vidage.min.js"&gt;&lt;/script&gt;
&lt;script&gt;
new Vidage(selector [, helperClass ]);
&lt;/script&gt;
```

##### ES6 way
```javascript
import Vidage from './Vidage';
new Vidage(selector [, helperClass ]);
```
