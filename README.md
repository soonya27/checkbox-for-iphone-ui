# checkbox-for-iphone-ui

### [githubpage](https://soonya27.github.io/modal.js/)


### HTML
```html
<div class="checkbox-wrap">
    <input type="checkbox" checked>
</div>
```


### CSS
```css
:root {
    /* 커스텀 */
    --checkboxWrapWidth: 60px;
    --checkboxWrapHeight: 34px;

    --checkbox-RoudPadding: 5px;
    
    
    --checkbox-RoudWidth: calc(var(--checkboxWrapHeight) - var(--checkbox-RoudPadding)*2);
    --round-moves: calc((var(--checkboxWrapWidth) - var(--checkbox-RoudPadding)*2) - var(--checkbox-RoudWidth));
}
```
