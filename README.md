# SomethingDigital_SkipToContent

A magento module that improves accessibility by adding a [skip to content](http://webaim.org/techniques/skipnav/) link. The link is visually hidden, but is visible to screen readers and appears when focused using TAB.

You'll need the following CSS (from html5bp) in your theme:
```css
.visuallyhidden {
  border: 0;
  clip: rect(0 0 0 0);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
}

.visuallyhidden.focusable:active,
.visuallyhidden.focusable:focus {
  clip: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  position: static;
  width: auto;
}
```
