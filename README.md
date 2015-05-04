# jquery-global-wrapper

If you use browserify or webpack and you already have a global jQuery in place, you can reference it with this wrapper instead of bundeling another jQuery.

Add the wrapper to your package.json depencencies:
```
"dependencies": {
  "jquery": "levito/jquery-global-wrapper"
}
```
jQuery plugins installed via npm will simply use the existing global jQuery.
