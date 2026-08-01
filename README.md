# NEPHTHYS_CLOUD

## Ultimate Cloud Destroyer

Complete Cloud Domination

## Features

### Container Escape (4 Methods)
- Privileged mount
- containerd socket (CVE-2020-15257)
- runc (CVE-2019-5736)
- Docker socket exposure

### Kubernetes Pwn
- Credential harvesting (kubeconfig, SA tokens)
- Node scanning
- Pod scanning
- Secret scanning
- RBAC scanning (roles, cluster roles)
- Ingress scanning
- Service account enumeration
- Privileged pod detection
- Secret exposure detection
- Persistent backdoor pod creation

### AWS Pwn
- Credential harvesting (EC2 metadata, env, files)
- S3 bucket enumeration (public detection)
- EC2 instance scanning
- IAM user/role enumeration
- RDS instance scanning
- Lambda function scanning
- Secrets Manager scanning
- Public S3 exploitation
- Backdoor IAM user creation

### GCP Pwn
- Credential harvesting (metadata, SA files)
- Storage bucket enumeration
- Compute instance scanning
- Public GCS exploitation
- Service account persistence

### Azure Pwn
- Credential harvesting (managed identity, env)
- Storage account scanning
- Public storage exploitation
- App registration persistence

### Stealth
- Random delays (0.1-2.0s)
- Random User-Agent rotation
- Random headers
- X-Forwarded-For spoofing

## Installation

```bash

pip install -r requirements.txt
python3 nephthys_cloud.py
