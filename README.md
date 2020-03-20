# Practice with COR (Two Methods: AJAX + JSONP)

## How to use

0. install node-dev
    `npm install -g node-dev`
1. download source code 
    `https://github.com/ReformedCola/cors.git`
2. get in qq.com and run server.js
    `cd cors/qq.com; node-dev server.js 8888`
3. get in jason.com and run server.js
    `cd ../frank.com; node-dev server.js 9999`
4. set hosts
    ```
    127.0.0.1 qq.com
    127.0.0.1 frank.com
    ```
5. open up both two pages qq.com:8888/index.html and jason.com:9999/index.html
6. please delete the two hosts you just set, otherwise you couldn not visit qq.com normally
