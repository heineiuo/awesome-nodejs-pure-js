# awesome-nodejs-pure-js

Many low level node.js libs written in c/c++ or dependent on native modules. That's awesome, but in some trade off case we need pure javascript lib.


## graphic (图形库)
#### image (图片处理)
* [jpeg-js](https://github.com/eugeneware/jpeg-js) A pure javascript JPEG encoder and decoder for node.js
* [upng.js](https://github.com/photopea/UPNG.js) Fast and advanced PNG (APNG) decoder and encoder
* [jimp](https://github.com/oliver-moran/jimp) An image processing library written entirely in JavaScript
* ⭐️ [node-pureimage](https://github.com/joshmarinacci/node-pureimage) Pure JS implementation of an image drawing and encoding api, based on HTML Canvas

#### video (视频)
* [node-mpeg2ts-parser](https://github.com/t6tn4k/node-mpeg2ts-parser) MPEG-2 TS parser in Node.js

#### captcha (验证码)
* [trek captcha](https://github.com/trekjs/captcha) A Lightweight Pure JavaScript Captcha for Node.js. No C/C++, No ImageMagick, No Canvas.
* [svg captcha](https://github.com/lemonce/svg-captcha) generate svg captcha in node

#### qr (二维码)
* [qr image](https://github.com/alexeyten/qr-image) Yet another QR code generator

#### font (字体)
* ~~[typr](https://github.com/photopea/Typr.js) process fonts in Javascript~~
* [opentype](https://github.com/nodebox/opentype.js) Read and write OpenType fonts using JavaScript
* [ttj.js](https://github.com/ynakajima/ttf.js) JavaScript font library for Node.js
* [BDF.js](https://github.com/victorporof/BDF.js) Simple library for reading Adobe Glyph Bitmap Distribution font files

#### math
* [js-2dmath](https://github.com/llafuente/js-2dmath) Fast 2d geometry math: Vector2, Rectangle, Circle, Matrix2x3 (2D transformation), Circle, BoundingBox, Line2, Segment2, Intersections, Distances, Transitions (animation/tween), Noise, Random numbers

## compress (压缩)
* [pako](https://github.com/nodeca/pako) high speed zlib port to javascript
* [tar](https://github.com/npm/node-tar) tar for node
* [snappyjs](https://github.com/zhipeng-jia/snappyjs) JavaScript implementation of Google's Snappy compression library
  

## net protocol (网络库)
* [ws](https://github.com/websockets/ws) Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js
* [eshttp](https://github.com/iefserge/eshttp)  Portable pure JavaScript ES6/2015 HTTP library
* [dns](https://github.com/tjfontaine/node-dns) Replacement dns module in pure javascript for node.js
* [ssh2](https://github.com/mscdex/ssh2) SSH2 client and server modules written in pure JavaScript for node.js
* [netcat](https://github.com/roccomuso/netcat)
* [node-x11](https://github.com/sidorares/node-x11)  X11 node.js network protocol client
* [http-parser](https://github.com/creationix/http-parser-js) This library parses HTTP protocol for requests and responses. It was created to replace http_parser.c since calling C++ function from JS is really slow in V8.

## system (系统)

* [ps-list](https://github.com/sindresorhus/ps-list) Get running processes. Works on macOS, Linux, and Windows.
* ~~[font-list](https://github.com/oldj/node-font-list) Current version supports macOS and Windows only, can not be used on Linux yet.~~

#### windows
* [node-winreg](https://github.com/fresc81/node-winreg) node module that provides access to the Windows Registry through the REG commandline tool
  
## file format (文件格式)
* [xlsx](https://github.com/SheetJS/js-xlsx)
* [jsPDF](https://github.com/MrRio/jsPDF)
* [pdf.js](https://github.com/mozilla/pdf.js)
* [pdfmake](https://github.com/bpampuch/pdfmake)
* [plist](https://github.com/TooTallNate/plist.js)
* [xmldom](https://github.com/jindw/xmldom) xml
* [file-type](https://github.com/sindresorhus/file-type) Detect the file type of a Buffer/Uint8Array 
* [mime](https://github.com/broofa/node-mime) mime type for javascript

#### data interchange format (数据交换格式)
* [bson](https://github.com/mongodb/js-bson) BSON is short for Binary JSON and is the binary-encoded serialization of JSON-like documents
* [protobuf.js](https://github.com/dcodeIO/protobuf.js) Protocol Buffers are a language-neutral, platform-neutral, extensible way of serializing structured data for use in communications protocols, data storage, and more, originally designed at Google
* [msgpack5](https://github.com/mcollina/msgpack5) 
* [msgpack-js](https://github.com/creationix/msgpack-js)
* [binary-extract](https://github.com/juliangruber/binary-extract) Extract a value from a buffer of json without parsing the whole thing

## text （文本处理）
* [jsdiff](https://github.com/kpdecker/jsdiff) A javascript text differencing implementation.

#### pinyin (拼音)
* [pinyinjs](https://github.com/sxei/pinyinjs) 一个实现汉字与拼音互转的工具库

#### char encode/decode (文本编码)
* [iconv-lite](https://github.com/ashtuchkin/iconv-lite) Convert character encodings in pure javascript.
* [base64](https://github.com/beatgammit/base64-js)
  
## crypto (加密)
* [sha.js](https://github.com/crypto-browserify/sha.js)
* [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) JsonWebToken implementation for node.js

## i18n (国际化)

#### polyfill
* [date-time-format-timezone](https://github.com/yahoo/date-time-format-timezone) Surgically polyfills timezone support in Intl.DateTimeFormat API
* [Intl.js](https://github.com/andyearnshaw/Intl.js) Compatibility implementation of the ECMAScript Internationalization API (ECMA-402) for JavaScript

## data structures and algorithms  
* [lru-cache](https://github.com/isaacs/node-lru-cache) A cache object that deletes the least-recently-used items.

#### data structures
* [long.js](https://github.com/dcodeIO/long.js) A Long class for representing a 64-bit two's-complement integer value.
* [LinkList](https://github.com/isaacs/yallist)
* [node-jumplist(skiplist)](https://github.com/superisaac/node-jumplist)
* [js-tree](https://github.com/wangzuo/js-tree)
* [Buckets-JS(collections)](https://github.com/mauriciosantos/Buckets-JS)
* [Data-Structures(collections)](https://github.com/Bishop92/JavaScript-Data-Structures) A library for data structure in JavaScript
* [lago(collections)](https://github.com/yangshun/lago) 🌴 Data Structures and Algorithms library for JavaScript.
* [dsjslib(collections)](https://github.com/monmohan/dsjslib) A library implementing several standard data structures and utilities

#### algorithms
* [fabonacci-layout](https://github.com/heineiuo/fabonacci-layout)
* [crc](https://github.com/alexgorbatchev/node-crc) Module for calculating Cyclic Redundancy Check (CRC)
* [buffer-crc32](https://github.com/brianloveswords/buffer-crc32) A pure javascript CRC32 algorithm that plays nice with binary data

## database

* [thalia](https://github.com/calvinmetcalf/thalia) pure js NOT in memory db
* [jinn-db](https://github.com/lasalvavida/jinn-db) A pure javascript, persistent key-value store for Node.js that supports out-of-core data access.
* [node-lsm](https://github.com/gutobortolozzo/node-lsm) log structured merge tree in pure node.js
* [node-leveljs](https://github.com/lemonhall/node-leveljs) LevelDB in pure JavaScript, a very immature work in progress
* [hyperdb](https://github.com/mafintosh/hyperdb) Distributed scalable database

---

Contribution welcome, please use issue to commit libs.

欢迎通过issue提交您推荐的库。
