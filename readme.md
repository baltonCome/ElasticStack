`Create a .env file and replace it with your own environment`

echo -n "Sample log entry" | python -c "import socket, sys; s=socket.socket(socket.AF_INET, socket.SOCK_STREAM); s.connect(('localhost', 5000)); s.send(sys.stdin.read().encode()); s.close()"