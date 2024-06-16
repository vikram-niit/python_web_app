# Python Web App

# Docker commands
sudo docker build -t python_web_image .
sudo docker run --rm -d -p 5000:5000 python_web_image
Ensure ip is 0.0.0.0 if running docker in wsl2
# To remove container
sudo docker rm -f 59d40ed783c3
sudo docker container ls

