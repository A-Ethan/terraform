# gitbook init

## 问题

Installing GitBook 3.2.3
C:\Users\20083\AppData\Roaming\npm\node_modules\gitbook-cli\node_modules\npm\node_modules\graceful-fs\polyfills.js:287
      if (cb) cb.apply(this, arguments)
                 ^

TypeError: cb.apply is not a function
    at C:\Users\20083\AppData\Roaming\npm\node_modules\gitbook-cli\node_modules\npm\node_modules\graceful-fs\polyfills.js:287:18
    at FSReqCallback.oncomplete (fs.js:169:5)

## 解决

  // fs.stat = statFix(fs.stat)
  // fs.fstat = statFix(fs.fstat)
  // fs.lstat = statFix(fs.lstat)

# gitbook build

gitbook build ./ ./docs

