[![caiuss](./logo/caiuss.png)](http://ionicabizau.github.io/CaiuSS)

# CaiuSS [![Support this project][donate-now]][paypal-donations]

A Minimalist and Civilized CSS framework.

If you want to include CaiuSS in your web page, download the [latest release](/dist) or [a release you choose](https://github.com/IonicaBizau/CaiuSS/releases) and include it on the page:

## Demo

Check out the [online demo](http://ionicabizau.github.io/CaiuSS) or download the `gh-pages` branch to see the demo.

[![](http://i.imgur.com/rfzstsM.png)](http://ionicabizau.github.io/CaiuSS)

```html
<link rel="stylesheet" href="path/to/caiuss.min.css">
```
## Elements
### Container
```html
<div class="container">
    ...
</div>
```
### Headings
```html
<h1>h1 heading</h1>
<h2>h2 heading</h2>
<h3>h3 heading</h3>
<h4>h4 heading</h4>
<h5>h5 heading</h5>
<h6>h6 heading</h6>
```
### Tables
```html
<table class="table">
    <thead>
        <tr>
            <th>#</th>
            <th>Name</th>
            <th>Username</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>1</th>
            <td>Alice</td>
            <td>@alice</td>
        </tr>
        <tr>
            <th>2</th>
            <td>Bob</td>
            <td>@bob</td>
        </tr>
        <tr>
            <th>3</th>
            <td>Carol</td>
            <td>@carol</td>
        </tr>
    </tbody>
</table>
```
### Forms
```html
<form class="form" action="">
    <div>
        <label>
            <span>Email:</span><br>
            <input type="email" placeholder="Your email" class="form-elm">
        </label>
    </div>
    <div>
        <label>
            <span>Password:</span><br>
            <input type="password" placeholder="Your password" class="form-elm">
        </label>
    </div>
    <div>
        <button class="btn bg-white">Login</button>
    </div>
</form>
```
### Buttons
```html
<button class="btn bg-red">Red</button>
<button class="btn bg-orange">Orange</button>
<button class="btn bg-yellow">Yellow</button>
<button class="btn bg-green">Green</button>
<button class="btn bg-blue">Blue</button>
<button class="btn bg-purple">Purple</button>
<button class="btn bg-gray">Gray</button>
<button class="btn bg-white">White</button>
<button class="btn bg-black">Black</button>
```
### Images
```html
<img class="img" src="images/1.jpg">
```

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Thanks

 - I thank my brother, [@GhitaB](https://github.com/GhitaB) who came with the idea for the project name.

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md