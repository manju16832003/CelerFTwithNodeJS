# CelerFTwithNODEJS
===============

#### Description

CelerFT is a file upload tool that allows you to upload up to 5 files at a time. CelerFT allows you to upload 
large files i.e serveral gigabytes in size to a backend web server. 

The CelerFT user interface is based on Javascript, the HTML5 File API, Web Workers, and XMLHTTPRequest Level 2.

The CelerFT backend web server is based on Node.js with Express.js.

The CelerFT backend can also be used with NGINX. In this configuration NGINX acts as a reverse proxy and the file uploading is offloaded 
to the NGINX web server. Once the file has been uploaded to the temporary directory by NGINX a x-file-name header is passed on to CelerFT
that has the path of the file to be processed.

##### Dependencies

CelerFT requires JQuery and the SparkMD5 library. The Node.js server requires the fs-extra, formidable, crypto, 
express and path modules.
