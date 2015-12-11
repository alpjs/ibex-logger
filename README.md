# auk-logger

```js
import Koa from 'koa';
import config from 'auk-config';
import logger from 'auk-logger';

const app = new Koa();
config(__dirname + '/config')(app);
logger(app);
```
