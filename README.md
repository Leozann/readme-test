<div align="center">
  
# Express + TypeScript Boilerplate
A modern, production-ready backend boilerplate designed for **small to medium applications**, internal engineering teams, and scalable enterprise level usage (non-microservice). Structured for clarity, long-term maintainability, and fast onboarding.

### Built With

[![Express][Express.js]][Express-url] [![TypeScript][TypeScript.js]][TypeScript-url] [![Vitest][Vitest.js]][Vitest-url] [![PNPM][PNPM.js]][PNPM-url] [![Docker][Docker.js]][Docker-url] [![Drizzle][Drizzle.js]][Drizzle-url] [![PostgreSQL][Postgres.js]][Postgres-url]

<!-- ### 🔎 Overview -->
This boilerplate eliminates the typical multi-day setup required for a clean, maintainable backend.  
Simply
<br>
**clone → init → start building**

</div>

### 🧩 Key Features

- **Production-ready architecture**
- **App instance separated from entry point**
  - Serverless compatible
  - Test-friendly (supertest can load the app without starting a server)
- **Fully type safe end-to-end development**
- **Ready for Docker & local machine development**
- **Cross-platform support (Windows + macOS)**
- **Built-in code quality tools**
  - Pre-configured linting + formatting
  - Example unit tests included
- **Service Repository design pattern**

Built for interns, juniors, and mid-level developers, while remaining clean enough for larger-scale use.

## 📚 Table of Contents

- [Boilerplate Information](#express--typescript-boilerplate)
- [Why This Boilerplate?](#-why-this-boilerplate)
- [Usage Guide](#-usage-guide)
  - [Clone Instruction](#-clone-instruction)
  - [Setup Instructions](#-setup-instructions)
  - [Docker Support](#-docker-support)
- [Folder Structure](#-folder-structure)
- Database Structure (see `database/readme`)
- Naming Conventions
- Additional Notes
- Contributors


## 📌 Why This Boilerplate?

Modern backend engineering requires:

- Clear, enforceable structure
- Easy onboarding for new developers
- Predictable patterns
- Strong testing support
- Production-ready defaults
- Long-term maintainability

This repository addresses all of these points, providing a robust foundation for stable projects within your department and for public use.

## 🚀 Usage Guide

### 🧪 Clone Repository

### 🚧 Initial Setup
> [!IMPORTANT]
> The initial setup process is mandatory.

This repository provides an automated configuration script that handles all required preparations, ensuring the application is correctly initialized and aligned across all environments and team members.

<details>

<summary>Show Instructions</summary>
<br>
Run the following command once before starting development, staging, or production:
<br>
&nbsp;

```sh
   pnpm run init:setup
```
</details>

### 🐳 Docker Support

## 📁 Folder Structure

```text
.
├── src/
│   ├── config/
│   ├── modules/
│   ├── utils/
│   └── app.ts
├── tests/
├── database/
└── ...
```

## 🏷 Naming Conventions

<!-- ## 📝 Additional Notes -->
> [!NOTE]
> Useful information that developers should know.

1. Commit prevention is enforced:
   <br>
   **You cannot push without associated test files** — this improves code quality.
3. Recommended editor: VS Code with:
   - ESLint
   - Prettier



[Express.js]: https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white
[Express-url]: https://expressjs.com
[TypeScript.js]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org
[Vitest.js]: https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white
[Vitest-url]: https://vitest.dev
[PNPM.js]: https://img.shields.io/badge/PNPM-F69220?style=for-the-badge&logo=pnpm&logoColor=white
[PNPM-url]: https://pnpm.io
[Docker.js]: https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com
[Drizzle.js]: https://img.shields.io/badge/Drizzle%20ORM-1A1A1A?style=for-the-badge&logo=drizzle&logoColor=yellow
[Drizzle-url]: https://orm.drizzle.team
[Postgres.js]: https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white
[Postgres-url]: https://www.postgresql.org
