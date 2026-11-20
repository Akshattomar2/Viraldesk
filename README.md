# ViralDesk

**ViralDesk** is a self-hosted social media management workspace for planning, creating, scheduling, and managing content across connected social channels.



## Highlights

- Manage multiple social channels from one workspace.
- Draft, organize, and schedule social media posts.
- Preview content before publishing.
- Collaborate on content workflows.
- Connect supported social platforms and integrations.
- Self-host the application and manage your own deployment.

Platform capabilities depend on the relevant provider APIs, permissions, and account type. Some providers may restrict particular publishing or analytics operations.

## Getting started

ViralDesk is a multi-service application. Review the deployment and environment configuration before starting it:

1. Install the Node.js version specified in the root `package.json` and enable the repository's specified package manager (`pnpm`).
2. Review `.env.example` and configure the required database, storage, authentication, and provider credentials.
3. Follow the upstream deployment documentation for the infrastructure services and provider setup required by this codebase: <https://docs.postiz.com/>
4. Install dependencies and run the development scripts defined in the root `package.json`.

For production, configure secrets through your deployment environment. Do not commit `.env` files, API keys, OAuth secrets, database credentials, or access tokens.

## Configuration notes

- Social integrations require credentials and permissions from each provider.
- Publishing support is subject to each platform's API availability and policies.
- Review the environment variables in `.env.example` before deployment.
- Keep database backups and secure uploaded media storage in production.
