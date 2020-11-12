#### 该文件只是对库jwt-decode的小程序适配

#### 直接下载js文件到小程序目录

```js
import weappJwt from './weapp-jwt.js'

var res = weappJwt(jwtData)

console.log(res)
```

#### 也可以直接用atob btoa（小程序默认不支持）

```js
import { weBtoa, weAtob } from './weapp-jwt.js'
```