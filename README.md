# Auto.fun

Press the fun button. Auto.fun is a platform featuring a Solana-based program for launching tokens with bonding curves, integrated with Raydium for liquidity, a backend server, and a web frontend.


## Key Features

*   **Token Launch & Bonding Curves:** Deploy new Solana tokens with automated market making via bonding curves.
*   **Raydium Integration:** Utilizes Raydium Vaults for managing liquidity.
*   **Event-Driven Updates:** Leverages Helius webhooks for real-time on-chain event processing.
*   **AI Integration:** Uses FAL for image generation and News API for event information.
*   **Monorepo Structure:** Organized codebase using TurboRepo and Bun workspaces.
*   **Local Development Environment:** Uses Docker Compose for easy setup of PostgreSQL, Redis, and MinIO.

## Packages
@@fyinformation=cc@@
This monorepo contains the following packages:

*   `packages/autodoc`: Automatic repository documentation generation.
*   `packages/client`: The Vite + React frontend application.
*   `packages/docs`: Project documentation.
*   `packages/program`: Solana programs (Anchor framework) for the core Auto.fun logic and Raydium Vault interactions.
*   `packages/server`: The Hono backend server handling API requests, authentication, and off-chain logic.
*   `packages/types`: Shared TypeScript types, constants, and IDLs across the frontend, server, and program interactions.

## Technology Stack

*   **Frontend:** React, Vite, TypeScript, TailwindCSS
*   **Backend:** Hono, TypeScript, Node.js
*   **Blockchain:** Solana, Anchor, Raydium
*   **Database:** PostgreSQL (via Drizzle ORM)
*   **Cache/Queue:** Redis
*   **Storage:** MinIO (S3 compatible)
*   **Build/Repo:** Bun, TurboRepo
*   **Infrastructure:** Docker


