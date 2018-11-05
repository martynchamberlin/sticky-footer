# Sticky Footer

The solution to creating a sticky footer is incredibly easy nowadays thanks to Flexbox. Have a DOM that follows this structure:

```html
<body>
  <div>
    Place all of your website in this div.
    It doesn't even have to have a class!
  </div>

  <footer>
    This footer will hug the bottom no matter what its height.
  </footer>
</body>
```

And then this CSS:

```css
html, body {
  height: 100%;
}

body {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
```

That's all there is to it. [You can view a demo here](http://sticky-footer.martynchamberlin.com). Enjoy!

