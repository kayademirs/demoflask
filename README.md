# demoflask
Build an image (Dockerize) and run on Docker container
Download project 

git clone https://github.com/kayademirs/demoflask.git

cd demoflask

Build image 

docker image build -t demoflask .

Run container 

docker run --rm --name demoflask -p 8082:8080 -d demoflask

Open browser http://localhost:8082/
