"# CSoundDockerBuilds" 


### To build using docker file follow these steps:

1. `docker build -t <name:tag> path_to_dockerfile` --> Builds image from docker file

2. `docker run --name <container_name> -it image` -->Runs the container in iteractive mode 

3. `docker cp  csound_test_run:/csound/Emscripten/Csound6.13.0-Web.zip .` -->Exports the emscripten build back to host
