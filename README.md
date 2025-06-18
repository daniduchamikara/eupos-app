# EUPOS - Euro Lanka Point of Sale System

EUPOS is a modern Point of Sale (POS) system developed for Euro Lanka. It is designed as a microservice-based architecture using Docker and Kubernetes, offering modular, scalable, and efficient retail management.

## 🚀 Features

- Inventory management
- Billing and invoicing
- User authentication
- Product catalog
- Sales reporting and analytics
- Containerized microservices

## 🛠 Tech Stack

- **Backend**: Node.js, Express.js / Spring Boot
- **Frontend**: React.js
- **Database**: MongoDB / MySQL
- **DevOps**: Docker, Kubernetes
- **Authentication**: JWT / OAuth2
- **Monitoring**: Prometheus + Grafana (optional)

## 📦 Microservices

Each service is deployed separately. Repositories (or folders) include:
- `eupos-inventory-service`
- `eupos-billing-service`
- `eupos-auth-service`
- `eupos-api-gateway`
- `eupos-frontend`

## 🧪 Getting Started (Local Development)

### Prerequisites

- Node.js / Java (depending on service)
- Docker & Docker Compose
- MongoDB or MySQL (locally or via container)

### Clone the Repository

```bash
git clone https://github.com/your-username/eupos.git
cd eupos
