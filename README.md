# zf1-Session-SaveHandler-Compression
Session Save Handler Compression

The compression created in order to support compression of Sessions by using Redis Cluster.

# How to use it

```
Zend_Session::setSaveHandler(new Zend_Session_SaveHandler_Compression());
Zend_Session::start();

```