# TSZ
Error-bounded Lossy Data Compressor For Float Double 

TSZ algorithm is come from SZ algorithm, Github url is  https://github.com/szcompressor .

Bellow is aspect of improvement :
  1) Better speed and size.
     SZ head size about 24 bytes, we are reduced to 2 bytes.
     we delete some no use code and some unnecessary function could be droped.
  2) Support multi-threads, interface is thread-safety.
  3) Remove 2D 3D 4D 5D function, only 1D be remained.
  4) Remove int8 int16 int32 and other datatype, only float double be remained.
  5) Optimize code speed
  
After modify, TSZ become faster、smaller and independent.  TSZ more suitable for small block data compression.

