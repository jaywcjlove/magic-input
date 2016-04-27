
# magic-input

CSS3 Styles for Checkbox and Radio Button inputs look prettier. with only one element. [Live demo](https://jaywcjlove.github.io/magic-input)


# Usage

```bash
$ npm install magic-input
```

Include `dist/magic-input.css` or `dist/magic-input.min.css` in your html. If your use [Stylus](https://github.com/stylus/stylus) use `magic-input.styl`

```html 
<link rel="stylesheet" type="text/css" href="dist/magic-input.min.css">
```

## Checkbox iPhone Style

![](https://raw.githubusercontent.com/jaywcjlove/magic-input/gh-pages/img/mg1.gif)

```html 
<input type="checkbox" class="mgc-switch mgc-sm" checked />
<input type="checkbox" class="mgc-switch"  />
<input type="checkbox" class="mgc-switch mgc-lg" checked />
```

## Checkbox

![](https://raw.githubusercontent.com/jaywcjlove/magic-input/gh-pages/img/mg2.gif)

```html 
<input type="checkbox" class="mgc" checked/> Default
<input type="checkbox" class="mgc mgc-primary" checked /> Primary
<input type="checkbox" class="mgc mgc-success" /> Success
<input type="checkbox" class="mgc mgc-info" checked /> Info
<input type="checkbox" class="mgc mgc-warning" checked /> Warning
<input type="checkbox" class="mgc mgc-danger" checked /> Danger
```


## Radios

![](https://raw.githubusercontent.com/jaywcjlove/magic-input/gh-pages/img/mg3.gif)

```html 
<input type="radio" name="radio3" class="mgr mgr-sm"/> Default
<input type="radio" name="radio3" class="mgr mgr-primary" /> Primary
<input type="radio" name="radio3" class="mgr mgr-success mgr-lg" checked/> Success
<input type="radio" name="radio3" class="mgr mgr-info mgr-sm" /> Info
<input type="radio" name="radio3" class="mgr mgr-warning" /> Warning
<input type="radio" name="radio3" class="mgr mgr-danger mgr-lg" /> Danger
```

## Sizing Class

`sm` for `small` , `lg` for `large`

**For Checkbox**

`mgc-sm` `mgc-lg`

**For Radio Button**

`mgr-sm` `mgr-lg`


## Colorize Class

**For Checkbox**

`mgc-primary` `mgc-info` `mgc-success` `mgc-warning` `mgc-danger`

**For Radio Button**

`mgr-primary` `mgr-info` `mgr-success` `mgr-warning` `mgr-danger`