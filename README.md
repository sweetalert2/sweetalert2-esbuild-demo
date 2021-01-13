# Demonstration of using [SweetAlert2](https://sweetalert2.github.io/) with [esbuild](https://esbuild.github.io/)


#### index.js:
```js
import Swal from 'sweetalert2'

Swal.fire('Hi from esbuild!')
```

#### Build:
```sh
esbuild app.jsx --bundle --outfile=bundle.js --define:process.env.NODE_ENV="\"production\""
```

---

Live result: https://sweetalert2.github.io/sweetalert2-esbuild-demo
