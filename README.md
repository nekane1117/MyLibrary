# MyLibrary

# snipets
- Add frame to the all selected html tag
```javascript
javascript:(function(){ var target = window.prompt("タグ名を指定", "div"); var color = window.prompt("色を指定", "red"); var tags = document.getElementsByTagName(target); for(i in tags){ tags[i].style.border = "1px solid " + color; } })();
```
