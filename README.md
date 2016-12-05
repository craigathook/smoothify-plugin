# SmoothifyPlugin

Sometimes HTML elements, when animated slowly, can look choppy since certain browsers round the motion to the nearest pixel. This is an extremely simple GSAP Plugin for using a 'smoothify' property that forces HTML elements to animate on sub-pixels.

Use bower:

```
bower install gsap-smoothify-plugin
```

Or include with a script tag:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/latest/TweenMax.min.js"></script>
<script src="js/SmoothifyPlugin.js"></script>
```

And then just add and set the 'smoothify' property to 'true'.

```js
TweenLite.to(target, 10, {x: 50, y:50, smoothify: true});
```