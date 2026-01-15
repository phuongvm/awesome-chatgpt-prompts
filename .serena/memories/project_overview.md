# Awesome ChatGPT Prompts Project Overview

## Purpose
A web application (prompts.chat) for managing, sharing, and discovering AI prompts. Originally created for ChatGPT, but works with Claude, Gemini, Hugging Face Chat, Llama, Mistral, and other AI models. The repository includes both the web application and a collection of prompts.

## Tech Stack

### Frontend
- **Framework**: Next.js 16.0.10
- **React**: 19.2.0
- **UI Components**: Radix UI, Tailwind CSS 4
- **State Management**: React Hook Form, Zustand (via dependencies)
- **Styling**: Tailwind CSS, class-variance-authority
- **Icons**: Lucide React
- **Editor**: Monaco Editor (@monaco-editor/react)
- **Markdown**: react-markdown, remark-gfm, MDX

### Backend
- **Runtime**: Node.js 24.x
- **Framework**: Next.js (API routes)
- **Database**: Prisma ORM
- **Authentication**: NextAuth.js 5.0 (beta)
- **File Storage**: AWS S3 (@aws-sdk/client-s3)
- **Logging**: Pino

### Additional Features
- **Internationalization**: next-intl
- **Theming**: next-themes
- **Error Tracking**: Sentry
- **AI Integration**: OpenAI SDK
- **MCP Support**: @modelcontextprotocol/sdk
- **Testing**: Vitest, Testing Library

## Project Structure
- `src/` - Next.js application source code
- `prisma/` - Database schema and migrations
- `public/` - Static assets
- `scripts/` - Setup and utility scripts
- `messages/` - Internationalization files
- `packages/` - Shared packages
- `prompts.csv` - Prompt data (CSV format)
- `PROMPTS.md` - Markdown format of prompts

## Key Features
- Prompt library and search
- User authentication (GitHub, Google, Apple, Azure AD, email/password)
- Private prompts support
- Categories, tags, comments
- AI search and generation
- MCP (Model Context Protocol) support
- Self-hosting with customizable branding
- Multi-language support

## Database
- Prisma ORM
- Supports multiple database providers
- Migrations via Prisma Migrate

## Deployment
- Vercel-ready
- Docker support
- Self-hosting guide available