# Loan prediction web application
Deployment of a loan prediction model on the web


I had to create a web application for a loan application prediction model (dissertation).

This application was deployed AWS  using **Flask** and **AWS EC2**.


Docker:
#---------------

docker build --tag lp-docker .
docker run -p5000:5000 lp-docker:latest
Open in Browser  -  http://localhost:5000/



