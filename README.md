# installation

```js

yarn add @creatrix/regExp

OR 

npm i @creatrix/regExp

```

# example

```js
import {regex_username,regex_phone} from '@creatrix/RegExp';
const var1=regex_username; <!-- RETURN /^[a-zA-Z0-9_.-]/ >
const var2=regex_phone; <!-- RETURN /^\+(?:[0-9] ?){6,14}[0-9]$/ >
```