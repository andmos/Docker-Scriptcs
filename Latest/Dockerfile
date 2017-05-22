FROM mono:latest

WORKDIR /opt/workdir/

RUN nuget install scriptcs -ExcludeVersion 

ENTRYPOINT ["mono", "/opt/workdir/scriptcs/tools/scriptcs.exe"]   