SASS Responsive No More Tables mixin
====================================
by [Frank Lang](https://github.com/franklang/). Based on [Responsive No More Tables](https://elvery.net/demo/responsive-tables/#no-more-tables) by [Simon Elvery](https://elvery.net/).


Usage
-----
```html
<div class="no-more-tables">
  <table>[...]</table>
</div>
```

```scss
@media screen and (max-width: 800px) {
  .no-more-tables {
    @include no-more-tables-core();
    @include no-more-tables-skin();
  }
}
```
