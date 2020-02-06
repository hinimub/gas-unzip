gas-unzip
=========

Google Apps Script上でパスワード付きZIPファイルを解凍するためのライブラリ

# Description
[`zlib.js`](https://github.com/imaya/zlib.js)の[`unzip.js`](https://github.com/imaya/zlib.js/blob/develop/src/unzip.js)から解凍に必要のない一部のヘッダ解析処理などを省いて、他の[`zlib.js`](https://github.com/imaya/zlib.js)を利用したライブラリ（[`UnzipGs`](https://github.com/tanaikech/UnzipGs)）よりも"わずかに"速く解凍します。

# Method
## unzip(blob, string)
基本的には、UnzipGsの[`unzip`](https://github.com/tanaikech/UnzipGs#unzip)と変わりませんが、第二引数には`object`ではなく`string`を渡します。\
また、現在第二引数が省略された場合の処理が未実装です。
