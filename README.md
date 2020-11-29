Clone rep and:

1.
<code>docker build -t fastapi:v1 .</code>

2.
<code>docker run --rm --name myfastapi -d -p 8080:8000 fastapi:v1</code>

3.
http://localhost:8080/

4.
<code>docker stop myfastapi</code>
