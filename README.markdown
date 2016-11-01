name
====

**mytest**
*This module is used to study*

Table of Contents
==============

* [Name](#name)
* [Status](#staus)
* [Version](#version)
* [Synopsis](#synopsis)
* [Description](#description)
* [Content Handler Directives](#content-handler-directives)
    * [mytest](#mytest)
* [Filter Directives](#filter-directives)
* [Variables](#variables)
* [Installation](#installation)
* [Compatibility](#compatibility)
* [Community](#community)
* [Changes](#changes)
* [TODO](#todo)
* [Copyright & License](#copyright--license)
* [See-also](#see-also)

Status
======


Version
=======

Synopsis
========

```nginx

   location /hello {
     mytest;
   }
```

Description
===========

This module is user for test of nginx


[Back to TOC](#table-of-contents)

Content Handler Directives
==========================

mytest
------
**syntax:** *mytest*

**default:** *no*

**context:** *location*

**phase:** *content*

[Back to TOC](#table-of-contents)

Filter Directives
=================
[Back to TOC](#table-of-contents)

Variables
=========
[Back to TOC](#table-of-contents)


Installation
============

```bash

   $ wget http://nginx.org/download/nginx-1.10.1.tar.gz
   $ tar -xzvf nginx-1.10.1.tar.gz
   $ cd nginx-1.10.1.tar.gz

   # Here we assume you would install you nginx under /opt/nginx/.
   $ ./configure --prefix=/opt/nginx \
       add-module=/path/to/ngx_http_mytest_module

   $ make -j2
   $ make install
```
[Back to TOC](#table-of-contents)


Compatibility
=============


[Back to TOC](#table-of-contents)

Community
=========

[Back to TOC](#table-of-contents)


Changes
=======

[Back to TOC](#table-of-contents)

TODO
====

[Back to TOC](#table-of-contents)

Copyright & License
===================

[Back to TOC](#table-of-contents)

See-also
========

[Back to TOC](#table-of-contents)
