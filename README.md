# Docker-Scriptcs
Dockerimage for running scriptcs.

Run The REPL: 

    docker run -it andmos/scriptcs 

Or a ``csx``file: 

    docker run -it -v /path/to/file.csx:/test --workdir /test andmos/scriptcs file.csx

[![Build Status](https://travis-ci.org/andmos/Docker-Scriptcs.svg?branch=master)](https://travis-ci.org/andmos/Docker-Scriptcs)
