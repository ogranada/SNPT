SNPT
====

Simple Node Project Tool
------------------------
This is a tool to create simple NodeJs projects.

Features
--------
* Create project folder
* create package.json file
* install server libraries (express, socket.io, express.io)
* create simple server file

Usage
-----

```bash
Usage: snpt [options] name

Options:
  -h, --help            show this help message and exit
  -x, --install-express
                        install express.js package
  -i, --install-socket-io
                        install socket.io package
  -e, --install-express-io
                        install express.io package
  -s, --create-simple-server
                        create server.js file with simple server code
  -v, --verbose         
```


Example
-------

```
sntp -e -s ProjectName
```

