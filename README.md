# x-redirect

A http(s) interface to custom url scheme.

## Usage

- `https://tech1savvy.github.io/x-redirect/?keyword` will redirect to the url assigned to that keyword in [index.html](index.html)
```html
case "keyword":
    window.location.href = "https://example.com";
    break;
```

## Current Assigned Redirects
- `niftiybooks`: `https://github.com/tech1savvy/react-component-gallery`
