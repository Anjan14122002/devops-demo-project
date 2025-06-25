# DevOps Demo Project

This is a Node.js app deployed via Docker on AWS EC2.

## How to Run

```bash
docker build -t anjan1412/devops-demo .
docker run -d -p 80:3000 anjan1412/devops-demo

---

#### 5. **Optional: Set up CI/CD with GitHub Actions**
Automate Docker build + push:
- Use `.github/workflows/docker.yml`
I can help you generate that too if needed.

---

Want help writing a proper `README`, `docker-compose.yml`, or setting up GitHub Actions? Just say the word.
 
