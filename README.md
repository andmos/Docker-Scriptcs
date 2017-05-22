# Docker-Scriptcs
Docker image for running scriptcs. The repo contais two versions, `Latest` and `Source`. `Latest` is, well, latest release of ScriptCS from NuGet, while `Source` builds ScriptCS from the [source repository](https://github.com/scriptcs/scriptcs).

Run The REPL: 

    docker run -it andmos/scriptcs:latest

Or a ``.csx``file: 

    docker run -it -v /path/to/file.csx:/test --workdir /test andmos/scriptcs:latest file.csx

[![Build Status](https://travis-ci.org/andmos/Docker-Scriptcs.svg?branch=master)](https://travis-ci.org/andmos/Docker-Scriptcs)
