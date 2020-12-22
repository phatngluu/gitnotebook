## Node.js: Getting Started

### Modern Javascript

#### .js and .mjs

```
const http = require('http'); # .js
import http from 'http'; # .mjs
```

#### setTimeout

Execute `func` after x miliseconds.

```
func(arg1, arg2,...)
setTimeout(func, delay, arg1, arg2,...)
```

Other functions: setImmediate (chạy ngay lập tức), setIntervel(chạy sau mỗi interval), 

Clear above functions: clearInterval, clearImmediate

#### Object Literals

```
const mystery = "answer";
const PI = Math.PI

const obj = {
	p1: 10,
	p2: 20,
	f1() {},
	f2: () => {},
	[mystery]: 42,
	PI,
}
```

Access value `42` by `obj.answer`

`PI,` is a shorter form of `PI : PI,`

#### Destructing and Rest/Spread


