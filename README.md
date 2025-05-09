# CuteRest
CuteRest is a REST client tool dedicated for JSON... and also for XML. 
Website available at http://dridk.github.io/cuterest/

![CuteRest under linux](https://raw.githubusercontent.com/dridk/cuterest/master/screenshot.png "cuterest")

## What it is
CuteRest is an opensource tool dedicated to communicate with a REST server. It's particulary useful to manage 
Json Request during developement step. Actually, They are several tool for this purpose. You can use plugins from
your browser, like [Postman](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm). or use [httpie](https://github.com/jakubroztocil/httpie) as command-line from your console. But those application doesn't provide
a tree view for Json or XML response. YOu only have raw data, and you must use another software, like 
[jsonviewer](http://jsonviewer.stack.hu/) to view your content as a tree.  
CuteRest have both. It's a REST client which have different view to parse the response.

Feature

* Http Verb supported : GET,POST,PUT,DELETE,HEAD,PATCH,OPTION 
* View as JSON Tree
* View as XML Tree 
* HTML Web rendering
* JSON syntax highlighter
* XML syntax highlighter
* Search by key or value inside the tree
* Authentification: Basic,NTLM version 2 and Digest-MD5 
* Proxy settings
* View History
* Save Request in Favorite
* Import & Export favorte 

## Windows
Windows binaries can be downloaded from here:
[CuteRest-win32-beta-0.1.exe](https://github.com/dridk/cuterest/releases/download/v0.1-beta/CuteRest-win32-beta-0.1.exe)


## MacOS X
Mac OS binaries can be downloaded from here:
[CuteRest-beta-0.1.dmg](https://github.com/dridk/cuterest/releases/download/v0.1-beta/CuteRest-beta-0.1.dmg)


## Linux

CuteRest works well on Linux. There is not yet package avaible for distribution. I will publish a debian package
as soon as possible. For now, you need to compile it as it's describe below. 

## from Source
Compiling on Windows, OSX, Linux, and FreeBSD are really easy. But cutrest need a least Qt5.4 . Older version will generate complain during the compilation. 
* Download the community Qt 5.4 SDK from [qt.io](http://www.qt.io/download/)
* Download the source code from master branch. 
* From Qt Creator , File > Open project  then select cuterest.pro
* Compile and run it by clicking on the Green button

If you want to install it on your system. Compile and install it from the command line by using qmake your Qt installation path. 
    
    qmake cuterest.pro
    make
    sudo make install

## Twitter

Follow me on Twitter: https://twitter.com/dridk

## Releases

* [Version beta 0.1 released](https://github.com/dridk/cuterest/releases/tag/v0.1-beta) - 2015-04-06

## Author
*  Schutz alias [@dridk](https://github.com/dridk) Create all the Qt code
* Eugene Trounev alias [@its](https://github.com/its) help for the design
* Lucas Bourneuf alias [@Aluriak](https://github.com/its) help for the Json Tree model 

## License

CuteRest is licensed under the GNU General Public License Version 3 or later.

