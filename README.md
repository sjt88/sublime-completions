# Sublime Snippets

## ES6

- `import`
```javascript
import * from 'module';
```
- `export`
```javascript
export { variable };
```
- `exportdefault`
```javascript
export default variable;
```

- `promise`  
```javascript
new Promise((resolve, reject) => {
  // content
}).then((arg) => {
  // content
}).catch(err => {
  // content
});
```

- `promisethen`
```javascript
.then((arg) => {
	// content
});
```

- `promisecatch`
```javascript
.catch(err => {
	// content
});
```

- `arrow`
```javascript
(arg) => {
	
};
```

- `proxy`
```javascript
new Proxy(target, handler);
```

- `class`
```javascript
class ClassName extends SubclassName {
  constructor(args) {
    // contents
  }
  
}

```

- `static`
```javascript
static methodName(args) {
  // contents
}

```

- `get`
```javascript
get propertyName(args) {
  // contents
}

```
- `set`
```javascript
set propertyName(args) {
  // contents
}

```

## CasperJS
- `caspcreate`
```javascript
var casper = require('casper').create({
  verbose: true,
  logLevel: 'debug'
});
```

- `caspstart`
```javascript
casper.start('about:blank', function(){
  // content
});
```

- `caspthen`
```javascript
casper.then(function() {
  // content
});
```

- `caspopen`
```javascript
casper.open('about:blank', function(response) {
  // content
});
```

- `caspthenopen`
```javascript
casper.thenOpen('about:blank', function(response) {
  // content
});
```

- `caspevaluate`
```javascript
casper.evaluate(function(args) {
  // content
}, args);
```

- `casprun`
```javascript
casper.run(function() {
 // content
});
```

- `casplog`
```javascript
casper.log('message', 'info');
```

- `caspwait`
```javascript
casper.wait(ms, function() {
  // content
});
```

- `caspwaitfor`
```javascript
casper.waitFor(function condition() {
  return true;
}, function then() {
  // do something
});
```

- `caspgethtml`
```javascript
casper.getHTML('selector');
```

- `caspon`
```javascript
casper.on('eventname', function(e) {
  // content
});
```

- `casptbegin`
```javascript
casper.test.begin('description', testcount, function(test) {
  // content
});
```

- `casptassert`
```javascript
[casper.]test.assert(true === false);
```

- `casptassertequals`
```javascript
[casper.]test.assertEquals(true, false);
```

- `casptdone` - casper.done(fn);
```javascript
[casper.]test.done();
```

- `casptcomment`
```javascript
[casper.]test.comment('comment');
```

