# &lt;love-heart&gt;

Pulsing love heart web component

#### Demo
Check out http://janantala.github.io/love-heart/

![love](https://raw.github.com/janantala/love-heart/master/img/love.gif)
```html
Made with <love-heart></love-heart> by me
```

### Apply your own CSS:

```html
Made with <love-heart class="blue" ></love-heart> by me
Made with <love-heart class="big" ></love-heart> by me
```

# Usage

1. Install love heart component:

  ```
  ❯ bower install love-heart
  ```

2. Import Web Components' polyfill:

	```html
	<script src="bower_components/platform/platform.js"></script>
	<link rel="import" href="bower_components/polymer/polymer.html">
	```

3. Import Custom Element:

	```html
	<link rel="import" href="bower_components/love-heart/love-heart.html">
	```

4. Start using it!

	```html
	<love-heart></love-heart>
	```

## Fallback

You can add love-heart component fallback which is visible before page load is complete:

```html
Made with <love-heart>love</love-heart> by Jan Antala
```

# License

The MIT License

Copyright (c) 2013 [Jan Antala](http://www.janantala.com)
