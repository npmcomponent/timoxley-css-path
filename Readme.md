*This repository is a mirror of the [component](http://component.io) module [timoxley/css-path](http://github.com/timoxley/css-path). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/timoxley-css-path`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# css-path

  Get absolute path to a DOM element as a CSS selector.

## Example

```html
<div class="page">
  <h3 id="header">Header Level 3</h3>
  <ul class="list">
     <li>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</li>
     <li>Aliquam tincidunt mauris eu risus.</li>
  </ul>
</div>
```
CSS path of first `li`:
```html
body > div.page:nth-child(1) > ul.list:nth-child(2) > li:nth-child(1)
```

## Licence

  MIT
