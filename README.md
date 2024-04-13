# sitemap-url-array
Receives a sitemap XML file from local filesystem and outputs URLs as Javascript array, to a filepath you specify.

## Installation

`npm i sitemap-url-array`

## Usage

```javascript
const convertSitemap = require('sitemap-url-array');
await convertSitemap('filepath/to/sitemap.xml', 'filepath/to/sitemap.json');
```

