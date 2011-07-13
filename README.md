#simple-http#

This creates a basic static http server that can be started from the command line, pointed to a directory and given a port.

##Requires:##

* npm
	* `npm update` - make sure to run npm update to get the node-static library.
	* `npm link` - to put "simple-http" in your path.
	

##Usage:##

`simple-http [-p &lt;port-number&gt;] [path]`

* _All arguments are optional._ 

* Running simple-http without any arguments will start an http server on port 8080 service the current working directory.

* To start a server on port 8081 and serves content in ~/Sites:
	
> > `$> simple-http -p 8081 ~/Sites`


