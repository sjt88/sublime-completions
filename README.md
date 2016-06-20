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
- `caspcreate` - var casper = casper.require('casper').create(config);
- `caspstart`- casper.start(url, fn);
- `caspthen` - casper.then(fn);
- `caspopen` - casper.open(url, fn);
- `caspthenopen` - casper.thenOpen(fn);
- `caspevaluate` - casper.evaluate(fn);
- `casprun` - casper.run(fn);
- `casplog` - casper.log(message, level);
- `caspwait` - casper.wait(ms, fn);
- `caspwaitfor` - casper.waitFor(fn condition, fn then);
- `caspgethtml`- casper.getHTML();
- `caspon` - casper.on(eventname, fn);
- `casptbegin` - [casper.]test.begin(description, testcount, fn);
- `casptassert` - [casper.]test.assert(value);
- `casptassertequals` - [casper.]test.assertEquals(value1, value2);
- `casptdone` - casper.done(fn);
- `casptcomment` - casper.comment(comment);

