gas-unzip
=========

Library for unzip ZIP files with passwords on Google Apps Script

# Description

By omitting some header analysis processing that is not necessary for decompression from [`unzip.js`](https://github.com/imaya/zlib.js/blob/develop/src/unzip.js) of [`zlib.js`](https://github.com/imaya/zlib.js), Unzips "slightly" faster than other libraries using [`zlib.js`](https://github.com/imaya/zlib.js) like [`UnzipGs`](https://github.com/tanaikech/UnzipGs).

# Usage

1. Select "Resources" > "Libraries..." in the Google Apps Script
editor.
2. Enter the project key `16TTROk_cAvIZoLxxHMe9J8SGHth0YV1WCugxKsSXsMJjqN_23vt99neW` in the "Find a Library" field, and choose "Select". 
3. Choose a version in the dropdown box, and choose gasunzip as the
identifier. 
4. Click the "Save" button.

# Method
## unzip (blob, string)
Basically, it is the same as [`unzip`](https://github.com/tanaikech/UnzipGs#unzip) of UnzipGs , but pass` string` instead of `object` in the second argument. \
Also, the processing when the second argument is omitted is not implemented at present.
