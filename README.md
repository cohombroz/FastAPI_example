Clone rep and:

<b>Step 1</b>

<code>docker build -t fastapi:v1 .</code>

<b>Step 2</b>

<code>docker run --rm --name myfastapi -d -p 8080:8000 fastapi:v1</code>

<b>Step 3</b>

Go to http://localhost:8080/

<b>Step 4</b>

<code>docker stop myfastapi</code>
