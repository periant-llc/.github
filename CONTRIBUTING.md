# Contributing to Periant

Thank you for your interest in contributing! We welcome all contributions, but before you get started, please take a moment to read through the following guidelines.

## Development Workflow

1.  **Clone the Repositories**: Clone both the `periant-core`, `periant-service-ai` repositories.
2.  **Install Dependencies**: Run `pnpm install` in the `periant-core` root.
3.  **Start Services**: Run `task start-full-stack` to start all necessary development services, including Supabase and the backend.
4.  **Run Dev Server**: Start the application you're working on, for example: `pnpm dev --filter=@apps/studio`.

## Creating a Pull Request

1.  Create a new branch for your feature or fix.
2.  Ensure your code adheres to our [TypeScript Standards](https://github.com/periant-llc/internal-docs/blob/main/.kiro/steering/typescript-standards.md) and [React Best Practices](https://github.com/periant-llc/internal-docs/blob/main/.kiro/steering/react-nextjs-best-practices.md).
3.  Write tests to cover your changes.
4.  Fill out the pull request template completely.
5.  Ensure all CI checks are passing before requesting a review.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.
