gas-unzip
=========

Library for unzip ZIP files with passwords on Google Apps Script

# Description

By omitting some header analysis processing that is not necessary for decompression from [`unzip.js`](https://github.com/imaya/zlib.js/blob/develop/src/unzip.js) of [`zlib.js`](https://github.com/imaya/zlib.js), Unzips "slightly" faster than other libraries using [`zlib.js`](https://github.com/imaya/zlib.js) like [`UnzipGs`](https://github.com/tanaikech/UnzipGs).

# Method
## unzip (blob, string)
Basically, it is the same as [`unzip`](https://github.com/tanaikech/UnzipGs#unzip) of UnzipGs , but pass` string` instead of `object` in the second argument. \
Also, the processing when the second argument is omitted is not implemented at present.
