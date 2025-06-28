# Snippets App

The **Snippets App** is a modern web application built with **Next.js 15** that allows users to save, organize, and access their favorite code snippets in one centralized location.

---

## 🚀 Getting Started

### Prerequisites

Ensure the following are installed:

- Node.js 18 or later  
- PostgreSQL  
- A package manager: npm, yarn, pnpm, or bun

---

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/snippets-app.git
cd snippets-app
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**

Create a `.env` file in the root directory:

```ini
DATABASE_URL="postgresql://USER:PASSWORD@localhost:5432/snippetsdb"
```

> Replace `USER`, `PASSWORD`, and `snippetsdb` with your PostgreSQL credentials.

4. **Generate and migrate Prisma schema**

```bash
npx prisma generate
npx prisma migrate dev --name init
```

5. **Run the development server**

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## ✨ Features

- Create, edit, and delete code snippets  
- Organize snippets by language or category  
- Full-text search and filters  
- Syntax highlighting  
- Responsive design for desktop and mobile  
- Built with Next.js 15 App Router and Server Actions  
- PostgreSQL + Prisma ORM backend

---

## 📁 Project Structure

```bash
app/            # App Router pages and layout
components/     # Reusable UI components
lib/            # Utility functions
prisma/         # Prisma schema and client
public/         # Static assets
styles/         # Tailwind CSS styles
```

---

## 🧰 Tech Stack

- **Framework:** Next.js 15 (App Router, Server Actions)  
- **Language:** TypeScript  
- **Database:** PostgreSQL  
- **ORM:** Prisma  
- **Styling:** Tailwind CSS  
- **UI Library:** shadcn/ui
