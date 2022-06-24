#

This is test npm package

# How to 


`npm i testFunction --save`

Then

```

import { testFunction } from 'testFunction';

testFunction({
    shadow_type: 'soft',
    padding: false
})

```

Options 2

* shadow_type - _hard | soft_ (Default to soft)
* padding - _boolean_ (Default to false)