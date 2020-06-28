# fixme.css

Add the `fixme.css` to your html header and check your website.
Search for red dashed borders which indicate different HTML issues.

## Use unpkg CDN

```html
<link rel="stylesheet" type="text/css" href="https://unpkg.com/fixme.css">
```

## Alternative hosts which provides the latest css file

### GitHub

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://raw.githubusercontent.com/jerolimov/fixme.css/master/fixme.css"
>
```

## Or use npm to install it locally

```bash
npm install --save fixme.css
```

If you use an package which can handle css import:

```typescript
import 'fixme.css';
```

Otherwise you need to copy it to your static/dist folder:

```
cp node_modules/fixme.css/fixme.css public/
```
