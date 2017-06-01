# themes-classname

```shell
npm i themes-classname --save
```

```js
var themesClassName = require('themes-classname')
themesClassName({
    themes: 'night',
    prefixClassName: 'm-dialog'
})
// " m-dialog--themes-night "

themesClassName({
    themes: 'night small',
    prefixClassName: 'm-dialog'
})
" m-dialog--themes-night m-dialog--themes-small "

themesClassName({
    themes: 'night small',
    prefixClassName: 'm-dialog',
    subClassName: '-mask'
})
// " m-dialog--themes-night m-dialog--themes-small "
themesClassName({
    themes: 'night small',
    prefixClassName: 'm-dialog'
}, '-mask')
// " m-dialog--themes-night m-dialog--themes-small "
```
