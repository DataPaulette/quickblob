# quickblob
Find and count unconnected blobs in an image really fast.

## Usage

Currently it's just testable with:

    make
  
It should open firefox with 2 pictures, the input and the picture with the blobs marked.

## TODO

- remove malloc calls and estimate memory to pre-allocate
- port to arduino and compare performances with openMV:

https://github.com/openmv/openmv/blob/master/src/omv/img/blob.c#L110
