# Web performance snippets

## CSS
### Disable all styles
```
document.⁠⁠querySelectorAll('style, link[rel="stylesheet"]').forEach(e => e.remove());
```
