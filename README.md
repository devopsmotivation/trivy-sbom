TRIVY SBOM
-------------

Trivy is like a detective for your software, especially when it comes to Docker images. 
Its main job is to make sure that the software you're using doesn't have any hidden vulnerabilities or security issues. 
Trivy is like the superhero that scans your software packages, identifies potential threats, and keeps your applications safe.


Commands : 
-------------

1. brew install trivy
2. docker pull nginx:latest
3. trivy image nginx:latest
3. trivy image --format spdx-json --output nginx-sbom.json nginx:latest


Links :
-------------
https://github.com/aquasecurity/trivy
https://aquasecurity.github.io/trivy/v0.46/getting-started/installation/
https://aquasecurity.github.io/trivy/v0.33/docs/sbom/

