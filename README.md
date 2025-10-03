Simple HTTP Server from [Launch School](https://launchschool.com/)

Run the server by typing the following command:

```
/usr/local/bin/bash http_server.sh
```

If you are using Bash version >= 4, then you can add `#!/bin/bash` to the top of the file, and run the server by first adding execute permissions, and then running the file.

```
chmod +x http_server.sh
```

and then

```
./http_server.sh
```

To connect using the single line option:

```
nc -v localhost 2345
Connection to localhost port 2345 [tcp/dbm] succeeded!
GET /lion.html
HTTP/1.1 200 OK

...html output

GET /
HTTP/1.1 404 Not Found

POST /lion.html
HTTP/1.1 400 Bad Request
```

To connect to the server via web browser, start the server and then visit the following URL:

`http://localhost:2345/leopard.html`
