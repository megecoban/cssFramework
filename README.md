# cssFramework
- Custom Named Color Palette


###### How should I use it?
Our usage recommendation is as follows:
1. add **reset.css** to the page.
2. add **root.css** to the page.
3. add **main.css** to the page.

Like this:
```html
<link href="/src/reset.css" rel="stylesheet">
<link href="/src/root.css" rel="stylesheet">
<link href="/src/main.css" rel="stylesheet">
```
---
*If you want to use your color or your variables in main.css, you can use this way:*
```html
<link href="/src/reset.css" rel="stylesheet">
<link href="/src/root.css" rel="stylesheet">
<link href="/src/yourroot.css" rel="stylesheet">
<link href="/src/main.css" rel="stylesheet">
```

Our main.css is use the variables so you **must** add our root.css before the main.css. If you want add your variables, you must add your root.css before the main.css and after the root.css.
