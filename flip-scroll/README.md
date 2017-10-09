jQuery/SASS Table Flip Scroll plug-in
=====================================
by [Anthony Den Drijver](https://github.com/tonydd) and [Frank Lang](https://github.com/franklang/). Based on [Flip Scroll Responsive Table](https://elvery.net/demo/responsive-tables/#flip-scroll) by [Simon Elvery](https://elvery.net/).


Usage
-----
```html
<div class="table-flip-scroll">
  <table>[...]</table>
</div>
```

```javascript
$.tableFlipScroll('.table-flip-scroll');
```

```scss
@media screen and (max-width: 800px) {
  .table-flip-scroll {
    @include table-flip-scroll-core();
    @include table-flip-scroll-skin();
  }
}
```


TODO:
-----
* Add a destroy method.
