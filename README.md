# dockerfileExample
Build a docker image of web server

1. Copy dockerfile content to local.
2. Run command ``` docker build -t <image name>:<tag> . --no-cacahe ``` to build an image.
3. Run command ``` docker run --name=<new container name> -d -p 5566:80 <image name>:<tag> ```.
4. Visit ``` http://hostip:5566 ``` by browser.
