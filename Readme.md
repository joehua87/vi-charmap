# vi-charmap
Vietnamese char map, a list of something like { 'ả': 'a', 'ô': 'o' }

## Usage

### With slugify
```js
const slugify = require('slugify')
const viCharMap = require('vi-charmap')

slugify.extend(viCharMap)

console.log(slugify('Việt nam', { lower: true })) // viet-nam
```
