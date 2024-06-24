# Weyneshof Project

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Weyneshof is a playground operation, serving as the main website, admin site, and registration site for the project. Developed with Next.js using the `AppRouter` and `create-t3-app`, it leverages modern web development practices and tools, including `pnpm` for package management and `shadcn/ui` for UI components.

## Features

- Server-side rendering and static site generation with Next.js.
- Modular and scalable project structure.
- Efficient package management with `pnpm`.
- Type-safe API routes and data fetching.
- Custom UI components with `shadcn/ui`.
- Adherence to conventional commits for structured commit messages.

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Package Manager**: [pnpm](https://pnpm.io/)
- **Bootstrap Tool**: [create-t3-app](https://create.t3.gg/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)

## Prerequisites

- [Node.js](https://nodejs.org/en/) (>= 14.x)
- [pnpm](https://pnpm.io/) (>= 6.x)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/weyneshof.git
   cd weyneshof
   ```

2. **Install dependencies:**

   ```bash
   pnpm install
   ```

3. **Run the development server:**

   ```bash
   pnpm dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Environment Variables

Create a `.env.local` file in the root directory and add your environment variables:

```
# Example:
DATABASE_URL=your-database-url
NEXT_PUBLIC_API_KEY=your-public-api-key
```

## Project Structure

The project structure follows best practices for a Next.js application:

```
weyneshof/
├── public/             # Static assets
├── src/
│   ├── app/            # app router
│       └── api/        # API routes
│   ├── components/     # Reusable components
│   ├── styles/         # Global styles
│   └── server/         # Server configuration
│       └── db/         # Database configuration
├── .env.local          # Environment variables
├── package.json        # Project metadata and scripts
└── pnpm-lock.yaml      # Lock file for pnpm
```

## Scripts

- `pnpm dev`: Runs the development server.
- `pnpm build`: Builds the application for production.
- `pnpm start`: Starts the production server.
- `pnpm lint`: Lints the codebase using ESLint.
- `pnpm test`: Runs the test suite.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) (`git commit -m 'feat: add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out if you have any questions or need further assistance. Happy coding!

---

**Maintainer**: [Lisa Scheers](https://github.com/LisaScheers)
