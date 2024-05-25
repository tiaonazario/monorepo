# Monorepo

Welcome to the Monorepo project! This repository serves as a template for a modern, full-stack monorepo setup using a variety of powerful technologies. It includes everything you need to kickstart your next web application with a cohesive, scalable development environment.

## Technologies Used

- **Next.js**: A React framework for server-side rendering and generating static websites.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **TRPC**: End-to-end typesafe APIs made easy.
- **Drizzle ORM**: A lightweight TypeScript ORM for SQL databases.
- **PNPM**: A fast, disk space-efficient package manager.
- **Auth.js**: Simple authentication for Next.js.
- **BiomeJS**: A modern, fast, and flexible JavaScript linter, formatter, and more.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js
- PNPM

### Installation

Clone the repository and install the dependencies using PNPM:

```bash
git clone https://github.com/yourusername/monorepo.git
cd monorepo
pnpm install
```
### Running the Development Server

Start the development server:

```bash
pnpm dev
```

Open http://localhost:3000 with your browser to see the result.

### Building for Production

To create a production build, run:

```bash
pnpm build
```

### Linting and Formatting

To lint and format your code, run:

```bash
pnpm lint
pnpm format
```

## Project Structure

The project structure follows a typical monorepo layout:

```bash
monorepo/
├── apps/
│   └── web/        # Next.js application
├── packages/
│   ├── ui/         # Shared UI components
│   ├── api/        # TRPC API
│   └── db/         # Drizzle ORM and database schemas
├── config/
│   ├── tailwind/   # TailwindCSS configuration
│   └── typescript/ # TypeScript configuration
├── .github/        # GitHub actions and workflows
├── .vscode/        # VSCode settings
├── package.json    # Root package.json
├── pnpm-workspace.yaml # PNPM workspace configuration
└── README.md       # This README file
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
Special thanks to the developers and maintainers of all the technologies used in this project.
