INSTALLATION STEPS FOR GOLANG [ LINUX ]

.

STEP-1 : Download the specific tar from this download https://golang.org/dl/

Example:
$ wget https://dl.google.com/go/go1.15.5.linux-amd64.tar.gz

.





STEP-2 : Untar the golang binary into /usr/local directory.

Example:

$ tar -xzvf go1.15.5.linux-amd64.tar.gz 

$ mv go /usr/local/

.


STEP-3 :  Setup the environment variables [GOROOT,GOPATH,PATH] for golang.

GOROOT [It is the variable that will keep where the go binary is installed]

GOPATH [It is the variable that will keep where the go-project is going to create]

PATH [Linux path variable]




Example:

$ export GOROOT=/usr/local/go

$ export GOPATH=$HOME/Projects

$ export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

you can add this lines to end of .profile file, after updating source the profile please source the profile
$ source ~/.profile

.

STEP-4 : Create your gopath .

$ mkdir -p $HOME/Projects/src
