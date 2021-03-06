
# Badgerly

```
    > bower install badgerly --save
```

<img align="left" height="150" style="margin-right: 30px;" alt="BADGERLY BADGER BADGE" src="https://s17.postimg.org/mshuxs24v/badgerly.png">

---
- Integrates easily with [Font Awesome](http://fontawesome.io/)!
- Fully implemented in CSS 3, no spacer images or other hackery.
- Simple to use CSS classes which can be extended.
- Implemented in SCSS, also available in plain CSS for your convenience.

## Check out the [Wall of Badges](https://jsfiddle.net/stevenmhunt/3krm64o1/)
<img alt="WALL OF BADGES" src="https://s11.postimg.org/nfqgfq09f/badges.png">

## Integrations
- [angular-badgerly](https://github.com/stevenmhunt/angular-badgerly) - Adds directive support for Badgerly, making it even easier (somehow) to create badges!

## Colors
Gold, Silver, Bronze

## Sizes
Tiny, Small, Medium, Large, Huge

## Ribbon Patterns
Red, Orange, Yellow, Green, Blue, Purple, Pink, Black, Rainbow, and a bunch of country flags!

Supports either a single ribbon or a lanyard with two visible ribbons.

## Examples

### [Round silver metal with a single purple ribbon](https://jsfiddle.net/stevenmhunt/wqyrq8a0/)
```html
  <div class="badge large">
    <div class="ribbon purple">
    </div>
    <div class="circle silver border">
      <i class="fa fa-tree"></i>
    </div>
  </div>
```

### [Diamond gold metal with a red lanyard](https://jsfiddle.net/stevenmhunt/0739du3f/)
```html
  <div class="badge large">
    <div class="lanyard">
      <div class="ribbon left red"></div>
      <div class="ribbon right red"></div>
    </div>
    <div class="diamond gold border">
      <i class="fa fa-star"></i>
    </div>
  </div>
```

## Contributing

Contributions and pull requests are welcome! Here are instructions on how to build the project:

- Make changes in the **badgerly.scss** file.
- Then, run `npm install` followed by `gulp sass` to transpile the SCSS file into CSS.
- Push the your changes to your fork and submit a PR.

## Credits
- <div>Badger icon made by <a href="http://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="http://www.flaticon.com" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>