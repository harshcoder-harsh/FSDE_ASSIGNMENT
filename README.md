# Instructions

1. Use SQLITE3 for database storage implementation
1. Use Prisma for ORM
1. Implement at least one full CRUD RESTful API
1. Deploy it on Render for backend and vercel for frontend
1. Resolve CORS issue if needed after deployment

## Deployment Architecture (Updated)

This project has been updated with a fully automated CI/CD pipeline using **GitHub Actions**.

- **Container Registry:** Amazon Elastic Container Registry (ECR)
- **Container Orchestration:** Amazon Elastic Container Service (ECS) with AWS Fargate
- **Automation:** The pipeline automatically builds, tags, and pushes the Docker image to ECR and deploys it to ECS on every push to the `main` branch...
