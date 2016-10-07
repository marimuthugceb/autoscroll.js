# AutoScroll
Auto Scroller for use in infinite scroll testing 

# Usage
1. Open console(chrome/firefox).
2. Run this script first (This will inject this library to the page)
```javascript
 var script = document.createElement("script");
 script.src = "https://rawgit.com/kishaningithub/autoscroll.js/master/AutoScroll.js";
 document.body.appendChild(script);
```
3. Do scrolling
```javascript
 var as = new AutoScroll();
 as.start({forward: true, speed: 'superfast'}); // Will start scrolling
 as.stop(); // Will stop scrolling
```

# Options
- forward 
  - true: Forward scrolling
  - false: Backward scrolling

- speed
 - slow
 - medium
 - fast
 - superfast
 - extreme
