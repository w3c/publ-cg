**Proposed Solution:** Use a `<div>` with display inline blocks https://codepen.io/bgedit/pen/MBRzoJ

**HTML**

```html
<body>
  <div class="line">
  <div class="speaker" aria-label="speaker">Hansan</div>
  <div class="dialog">Baba, I need to talk to you.</div>
  </div>
    <div class="line">
  <div class="speaker" aria-label="speaker">Baba</div>
  <div class="dialog">Isn't that what we are doing right now?</div>
  </div>
</body>
```
**CSS**

```css
body {
  font-size: 1.06em;
  line-height: 1.5;
  max-width: 711px;
  margin: auto;
  padding: 10px; }

div.speaker {
 width: 15%;
 min-width: 100px; 
 display: inline-block;
 margin-top: .5em;
 margin-right: 1em;
 text-transform: uppercase;
 font-weight: 600;
 float: left;
}

div.dialog {
 display: inline-block;
 width: 65%;
 margin-top: .5em;
 min-width: 400px;
}

div.line {
  display: block;
  margin-top: 1em;
}
```

**Known exceptions to solution:** Kindle may force justify lines or experience issues with float.

**Reading system testing:**

**Accessibility advantages:**

**Accessibility disadvantages:**

**Mobile compatibility advantages:**

**Mobile compatibility disadvantages:**

