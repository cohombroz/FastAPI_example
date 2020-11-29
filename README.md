Clone rep and:

Step 1
<code>docker build -t fastapi:v1 .</code>

Step 2
<code>docker run --rm --name myfastapi -d -p 8080:8000 fastapi:v1</code>

Step 3
Go to http://localhost:8080/

Step 4
<code>docker stop myfastapi</code>
