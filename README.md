# Docker-with-Flask

## RUN 
1. Build an image out of Dockerfile. Pass in the -t parameter to name the image. <br>
    `docker build -t sample .`
2. To verify the image built. <br>
    `docker images`
3. Run the docker container. <br>
    `docker run --name flask_app  -p 8000:5000 sample`
4. Open the browser and type: <br>
   [http:://127.0.0.1:8000/](http:://127.0.0.1:8000/) <br>
   
