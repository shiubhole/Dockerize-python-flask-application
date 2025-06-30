# Dockerize-python-flask-application
# Run the script:-

curl localhost:5000

docker build -t flask-app .

docker run -d -p 5000:5000 --name flask-container flask-app or docker container run --name flask-container -it -d -p 5000:5000

docker logs -f flask-container
