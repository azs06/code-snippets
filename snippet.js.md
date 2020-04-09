```
function foo(x) {
	return {
		true: 'foo',
		[x === 'bar'] : 'baz',
		[x === 'quux'] : 'fruy',
	}[true];
}

console.log(foo());
```
