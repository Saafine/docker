Make sure docker / docker compose is installed
Make sure Security Groups on AWS are set up correctly
Run chmod +x init.sh and sudo ./init.sh

# Troubleshooting:
Couldn't connect to Docker daemon at http+docker://localhost - is it running?
- try:
service docker restart 
OR
sudo

# How to fix docker: Got permission denied while trying to connect to the Docker daemon socket
sudo usermod -aG docker $USER
