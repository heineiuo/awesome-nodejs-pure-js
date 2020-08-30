# awesome-nodejs-pure-js[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Many low level node.js libs written in c/c++ or dependent on native modules. That's awesome, but in some trade off case we need pure javascript lib.


## graphic (图形库)
#### image (图片处理)
* [jpeg-js](https://github.com/eugeneware/jpeg-js) A pure javascript JPEG encoder and decoder for node.js
* [upng.js](https://github.com/photopea/UPNG.js) Fast and advanced PNG (APNG) decoder and encoder
* [node-pnglib](https://github.com/Lellansin/node-pnglib) Pure Javascript lib for generate PNG, Node.js version for PNGlib.
* [jimp](https://github.com/oliver-moran/jimp) An image processing library written entirely in JavaScript
* ⭐️ [node-pureimage](https://github.com/joshmarinacci/node-pureimage) Pure JS implementation of an image drawing and encoding api, based on HTML Canvas
* [look-same](https://github.com/gemini-testing/looks-same) Node.js library for comparing images
* [omggif](https://github.com/deanm/omggif) JavaScript implementation of a GIF 89a encoder and decoder
* [gifuct-js](https://github.com/matt-way/gifuct-js) Simple to use javascript .GIF decoder/parser

#### video (视频)
* [node-mpeg2ts-parser](https://github.com/t6tn4k/node-mpeg2ts-parser) MPEG-2 TS parser in Node.js
* [whammy.js](https://github.com/antimatter15/whammy/blob/master/whammy.js) A real time javascript webm encoder based on a canvas hack
* [mp4-stream](https://github.com/mafintosh/mp4-stream) Streaming mp4 encoder and decoder
* [mp4-box-encoding](https://github.com/jhiesey/mp4-box-encoding) mp4 header reading and writing using the abstract-encoding interface

#### captcha (验证码)
* [trek captcha](https://github.com/trekjs/captcha) A Lightweight Pure JavaScript Captcha for Node.js. No C/C++, No ImageMagick, No Canvas.
* [svg captcha](https://github.com/lemonce/svg-captcha) generate svg captcha in node

#### qr (二维码)
* [jsQR](https://github.com/cozmo/jsQR) A pure javascript QR code reading library. This library takes in raw images and will locate, extract and parse any QR code found within
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
* [jszip](https://github.com/Stuk/jszip) Create, read and edit .zip files with Javascript
* [tar](https://github.com/npm/node-tar) tar for node
* [tar-stream](https://github.com/mafintosh/tar-stream)  tar-stream is a streaming tar parser and generator.
* [snappyjs](https://github.com/zhipeng-jia/snappyjs) JavaScript implementation of Google's Snappy compression library
* [gzipme](https://github.com/caio-ribeiro-pereira/gzipme) A simple way to gzip your files

## net protocol (网络库)
* [ws](https://github.com/websockets/ws) Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js
* [eshttp](https://github.com/iefserge/eshttp)  Portable pure JavaScript ES6/2015 HTTP library
* [dns](https://github.com/tjfontaine/node-dns) Replacement dns module in pure javascript for node.js
* [ssh2](https://github.com/mscdex/ssh2) SSH2 client and server modules written in pure JavaScript for node.js
* [netcat](https://github.com/roccomuso/netcat)
* [node-x11](https://github.com/sidorares/node-x11)  X11 node.js network protocol client
* [http-parser](https://github.com/creationix/http-parser-js) This library parses HTTP protocol for requests and responses. It was created to replace http_parser.c since calling C++ function from JS is really slow in V8.

#### NAT
* [stun](https://github.com/nodertc/stun) Session Traversal Utilities for NAT (STUN) server. Implements RFC5389 with partial support RFC5766, RFC5245, RFC5780.
* [stun](https://github.com/enobufs/stun) STUN (Simple Traversal of UDP through NAT: RFC3489)
* [turn-js](https://github.com/nicojanssens/turn-js) implements (most of) the features specified in RFC 5766

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
* [Binary plist](https://github.com/ladinu/bplist) Binary plist parser and creator for node.js
* [sax-js](https://github.com/isaacs/sax-js) A sax style parser for JS
* [xmldom](https://github.com/jindw/xmldom) A PURE JS W3C Standard based(XML DOM Level2 CORE) DOMParser and XMLSerializer.
* [file-type](https://github.com/sindresorhus/file-type) Detect the file type of a Buffer/Uint8Array 
* [mime](https://github.com/broofa/node-mime) mime type for javascript
* [css](https://github.com/reworkcss/css) CSS parser / stringifier for Node.js
* [gradle](https://github.com/ninetwozero/gradle-to-js) A quick & dirty Gradle build file to JavaScript object parser
* [.properties](https://github.com/gagle/node-properties) .properties parser/stringifier.
* [csv-parser](https://github.com/mafintosh/csv-parser) Streaming csv parser inspired by binary-csv that aims to be faster than everyone else

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

#### char encode/decode (编解码)
* [iconv-lite](https://github.com/ashtuchkin/iconv-lite) Convert character encodings in pure javascript.
* [base64](https://github.com/beatgammit/base64-js)
  
## crypto (加密)
* [sha.js](https://github.com/crypto-browserify/sha.js)
* [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) JsonWebToken implementation for node.js
* [keypair](https://github.com/juliangruber/keypair) Generate a RSA PEM key pair from pure JS
* [AES-js](https://github.com/ricmoo/aes-js) A pure JavaScript implementation of the AES block cipher and all common modes of operation for node.js
* [BLAKE2s](https://github.com/dchest/blake2s-js) BLAKE2s cryptographic hash function in JavaScript


## i18n (国际化)

#### polyfill
* [date-time-format-timezone](https://github.com/yahoo/date-time-format-timezone) Surgically polyfills timezone support in Intl.DateTimeFormat API
* [Intl.js](https://github.com/andyearnshaw/Intl.js) Compatibility implementation of the ECMAScript Internationalization API (ECMA-402) for JavaScript
* [node-opencc](https://github.com/compulim/node-opencc) Translates between Traditional and Simplified Chinese in pure Node.js

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
* [uint32](https://github.com/fxa/uint32.js) An javascript implementation of bitwise uint32 operations
* [tiny-queue](https://github.com/nolanlawson/tiny-queue) A simple FIFO queue implementation as a linked list. The main benefit is to avoid doing shift() on an array, which may be slow.

#### algorithms
* [dsp.js](https://github.com/corbanbrook/dsp.js) Digital Signal Processing 
* [fourier-transform](https://github.com/scijs/fourier-transform) Minimalistic and efficient FFT implementation
* [fibonacci-layout](https://github.com/heineiuo/fibonacci-layout)
* [crc](https://github.com/alexgorbatchev/node-crc) Module for calculating Cyclic Redundancy Check (CRC)
* [buffer-crc32](https://github.com/brianloveswords/buffer-crc32) A pure javascript CRC32 algorithm that plays nice with binary data
* [algorithms.js](https://github.com/felipernb/algorithms.js) Traditional Computer Science algorithms and data structures implemented in JavaScript
* [uint64be](https://github.com/mafintosh/uint64be) Encode / decode big endian unsigned 64 bit integers
* [color-diff](https://github.com/markusn/color-diff) Implements the CIEDE2000 color difference algorithm, conversion between RGB and LAB color and mapping all colors in palette X to the closest color in palette Y based on the CIEDE2000 difference.

## database

* [thalia](https://github.com/calvinmetcalf/thalia) pure js NOT in memory db
* [jinn-db](https://github.com/lasalvavida/jinn-db) A pure javascript, persistent key-value store for Node.js that supports out-of-core data access.
* [node-level](https://github.com/heineiuo/node-level) A pure js key-value storage engine based on LSM, inspired by Leveldb.
* [node-lsm](https://github.com/gutobortolozzo/node-lsm) log structured merge tree in pure node.js
* [node-leveljs](https://github.com/lemonhall/node-leveljs) LevelDB in pure JavaScript, a very immature work in progress
* [hyperdb](https://github.com/mafintosh/hyperdb) Distributed scalable database

---

Contribution welcome, please use issue to commit libs.

欢迎通过issue提交您推荐的库。

## License

Licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
