# ViralDesk

**ViralDesk** is a self-hosted social media management workspace for planning, creating, scheduling, and managing content across connected social channels.

> **Open-source attribution:** ViralDesk is a branded derivative of [Postiz](https://github.com/gitroomhq/postiz), an open-source social media management platform. The upstream project and its contributors retain their original copyrights. This repository preserves the upstream AGPL-3.0 license and applicable notices. ViralDesk's branding does not imply endorsement by the Postiz maintainers.

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

## License

This project is distributed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. See [`LICENSE`](./LICENSE) for the complete license text. Preserve copyright, attribution, and license notices when modifying or redistributing the software.

## Upstream project

- Original project: <https://github.com/gitroomhq/postiz>
- Upstream documentation: <https://docs.postiz.com/>
- Upstream license: AGPL-3.0

ViralDesk's product name and branding are a downstream customization; they do not change the license or ownership of the upstream code.
