# 🛡️ Welo Guard

**Welo Guard** is a secure, scalable vault management system built for enterprise-grade document protection, fine-grained permissioning, and audit-grade traceability. It offers zero-trust access controls, real-time activity tracking, and seamless integration with your identity provider and file storage systems.

---

## 🚀 Features

- 🔐 **OAuth 2.0 Login Flow**  
  Modern authentication layer for secure SSO and token-based access

- 📁 **Vault Creation & Access Controls**  
  Create encrypted vaults with role-based and time-bound access

- 🧠 **Audit Logs**  
  Immutable audit trails for every interaction—who accessed what and when

- 🖥️ **Web Dashboard**  
  Responsive frontend for managing vaults, users, and policies

- 🛠️ **Developer API**  
  RESTful endpoints for vault CRUD, permissions, and audit visibility

- 📡 **Real-Time Activity Feed**  
  WebSocket-enabled activity streams for live monitoring

---

## 🧱 Tech Stack

| Layer        | Tech                           |
|--------------|--------------------------------|
| Frontend     | React + TypeScript + Tailwind  |
| Backend      | Node.js + Express              |
| Auth         | OAuth 2.0 + JWT                |
| Database     | PostgreSQL + Prisma ORM        |
| Realtime     | Socket.IO                      |
| Infrastructure | Docker, Terraform, GitHub Actions |

---

## ⚙️ Getting Started

### Prerequisites

- Node.js v18+
- PostgreSQL (local or Docker)
- Yarn or npm

### Setup

```bash
# Clone the repo
git clone https://github.com/your-org/welo-guard.git
cd welo-guard

# Install dependencies
yarn install

# Configure environment variables
cp .env.example .env

# Migrate and seed database
yarn prisma migrate dev
yarn seed

# Run the app
yarn dev
Visit http://localhost:3000 to open the app locally.

🧪 Testing
bash
Copy
Edit
# Unit + integration tests
yarn test

# Lint and format
yarn lint
yarn format
