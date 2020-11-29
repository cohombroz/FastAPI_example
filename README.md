1.
docker build -t fastapi:v1 .

2.
docker run --rm --name myfastapi -d -p 8080:8000 fastapi:v1

3.
http://localhost:8080/

4.
docker stop myfastapi