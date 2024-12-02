# How to run

### Server
```
python Server.py server_port
```

example:
```
python Server.py 10857
```

### Client
```
python ClientLauncher.py server_host server_port RTP_port video_file
```
server host = IP,
server port = port number of server,
RTP port = port for client (pick any),
video_file = movie.Mjpeg (for our purposes)

example:
```
python ClientLauncher.py 192.168.4.78 10857 4054 movie.Mjpeg
```