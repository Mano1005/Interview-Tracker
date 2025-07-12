Interview Tracker – Cloud Engineering 
 🌐 Project Overview
 This is a cloud-engineered, two-tier web application designed to log and manage job 
interviews using AWS-native services. The architecture separates the web frontend from 
the backend API, with persistent data stored in a managed database. It demonstrates 
essential cloud engineering skills using services like EC2, RDS, and system automation 
via Gunicorn and systemd.
 🚀 Key Features
 • Deployed on Amazon EC2 with Gunicorn and systemd
 • Database hosted on Amazon RDS (MySQL/PostgreSQL)
 • CORS-enabled REST API
 • Fully CRUD-capable with proper error handling
 • Monitoring via CloudWatch
 🧠 Cloud Engineer Highlights
 • ⚙￿ Real-world Linux service management (Gunicorn + systemd)
 • ☁￿ Hosted services using EC2, RDS, and S3
 • 🔒 API security (CORS, HTTPS)
 • 🔄 End-to-end CI/CD readiness (GitHub + systemctl pull)
 • 🧩 Easily extendable with VPC, Secrets Manager, IAM role.
 🌱 Future Improvements
 • IAM-based DB secret access (Secrets Manager / SSM)
 • CI/CD with GitHub Actions + EC2 deployments
 • Replace EC2 with ECS Fargate (for containerization)
 • Enable user auth via Amazon Cognito
 • Add metrics export via CloudWatch / Prometheus
 ✅ Conclusion
This project demonstrates a scalable, cloud-native interview tracking solution using core 
AWS services and open-source technologies. It’s ideal for Cloud Engineers who want 
hands-on experience with real deployment patterns, security considerations, and 
infrastructure design# Interview-Tracker
