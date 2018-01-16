### Type Check Of Javascript

#### How To Use
```
<script src="path/to/typo.js"></script>
```
THEN

```
	typo.isArray([]);         // true
	typo.isObject({});			// true
	typo.isString('');			// true
	typo.isDate(new Date());	// true
	typo.isRegExp(/test/i);		// true
	typo.isFunction(function () {}); // true
	typo.isBoolean(true); // true
	typo.isNumber(1);	// true
	typo.isNull(null);	// true
	typo.isUndefined();	// true
```

