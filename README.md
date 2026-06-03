
## Getting Started
---
## install command : npx create-next-app@latest

First, run the development server:

```bash
npm run dev

# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Learn More

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

---

## 🔐 Better Auth Setup (Next.js + MongoDB)
### 🚀 Installation
npm install better-auth

### ⚙️ Setup Steps
1. Create a .env file in the root directory
2. Add your secret key in .env
3. Set base URL for local development
4. BETTER_AUTH_URL=http://localhost:3000
5. Create Better Auth instance
👉 src/lib/auth.js
---

### Configure database connection
6. Install MongoDB adapter
7. npm install @better-auth/mongodb-adapter
Connect MongoDB and complete adapter setup