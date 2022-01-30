# Modals
To put a modal into your site, create a div element with the class `sw-modal`, and a child div with the class `sw-modal-content`. It should look like this:
```html
<div class="sw-modal">
    <div class="sw-modal-content">
        Your content goes here...
    </div>
</div>
```

By default, modals are hidden, but you can inject a little bit of JavaScript in order to make them clickable:
```html
<button class="sw-button" id="button" onclick="document.getElementById('modal').style.display = block">Click me!</button>
<div class="sw-modal" id="modal">
    <div class="sw-modal-content">
        <span id="text" onclick="document.getElementById('modal').style.display = none">Click me to hide.</span>
    </div>
</div>
```
