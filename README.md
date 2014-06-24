hellogo
=======

A simple, test repository to test Go (or a brand new install of Go and whether the Go workspace works)

An excellent summary of a Go workspace setup: [http://stackoverflow.com/a/10142340/974381](http://stackoverflow.com/a/10142340/974381)

Basically after you create the base workspace folder (and set the $GOPATH environment variable):
*Note: this example uses this exact repository*

    mkdir -p $GOPATH/src/github.com/viktorbenei/hellogo
    cd $_
    git clone https://github.com/viktorbenei/hellogo.git
    
That's all.
