# Flask Secure App 🐳🔐

A simple Flask app containerized with Docker and scanned using Trivy and Snyk.

## Run Locally
```bash
docker build -t flask-secure-app .
docker run -p 5000:5000 flask-secure-app
