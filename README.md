## Scanning Docker Images with Trivy

To scan the `flask-app` Docker image for vulnerabilities, run:

```bash
docker run --rm -v /var/run/docker.sock:/var/run/docker.sock aquasec/trivy image flask-app
