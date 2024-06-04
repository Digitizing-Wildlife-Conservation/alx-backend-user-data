0x01. Basic authentication Back-end Authentification Cohort.              

This project involves tasks for learning user authentication using the Basic authentication scheme. First, set up and start the server by installing the required packages and running the application with the specified host and port. Then, you can use the API by sending a GET request to check the status endpoint. Here are the commands for setup and usage:

Setup and start the server:

powershell
Copy code
bob@dylan:~$ pip3 install -r requirements.txt
bob@dylan:~$ API_HOST=0.0.0.0 API_PORT=5000 python3 -m api.v1.app
 * Serving Flask app "app" (lazy loading)
Use the API (in another tab or your browser):

powershell
Copy code
bob@dylan:~$ curl "http://0.0.0.0:5000/api/v1/status" -vvv
*   Trying 0.0.0.0...
* TCP_NODELAY set
* Connected to 0.0.0.0 (127.0.0.1) port 5000 (#0)
> GET /api/v1/status HTTP/1.1
> Host: 0.0.0.0:5000
> User-Agent: curl/7.54.0
> Accept: */*
< HTTP/1.0 200 OK
< Content-Type: application/json
< Content-Length: 16
< Access-Control-Allow-Origin: *
< Server: Werkzeug/1.0.1 Python/3.7.5

                                           -Happy Coding-
