REST Library is a test library for HTTP/REST, primarily designed for [Robot Framework](http://code.google.com/p/robotframework/).

It enables HTTP dialogues using HTTP verbs, setting request headers and verifying the response headers and body.

It includes (optional) support for parsing the body (currently requiring lxml). Apart from XML support it works with both Python and Jython.

## Install ##

You can install the latest trunk by invoking:

```
$ sudo easy_install http://robotframework-restlibrary.googlecode.com/svn/trunk#egg=RestLibrary-dev
```

Or manually by checking out [the source code](http://code.google.com/p/robotframework-restlibrary/source/checkout) and then do:

```
$ sudo python setup.py install
```