Built and ran docker container containing Flask web app, and deployed locally using port forwarding.

After enabling port forwarding on the lambda server at port 1234, I ran commands:
```
$ docker build -t flask-tutorial:latest .
$ docker run -d -p 1234:1234 flask-tutorial
```

I was then able to access the flask app at localhost:1234. I modified the port of the flask app to be 1234 as well.
