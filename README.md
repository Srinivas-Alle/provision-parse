# provision-parse

To parse Mobile provision files using javascript.

## How to Use

```
const parse = require('provision-parse');

parse('/provisiobs/app.mobileprovision',(info) => {
  console.dir(info);
  /* {
    uuid:,
    team:{
      name:,
      id:,
    },
    appid,
    name,
    expiryDate,
    type,
    cers

  }*/

});
```

Thanks to https://github.com/zhetengbiji/mobileprovision-parse
