# Code Style and Conventions for Awesome ChatGPT Prompts

## TypeScript Standards
- **TypeScript**: 5.x
- **Strict Mode**: Enabled
- **Type Safety**: Use Zod for validation (zod ^4.1.13)
- **Type Hints**: Required for function parameters and returns

## React/Next.js Conventions
- **React**: 19.2.0 (latest)
- **Next.js**: 16.0.10 (App Router)
- **Components**: Functional components with TypeScript
- **Styling**: Tailwind CSS 4 with class-variance-authority
- **Forms**: React Hook Form with Zod validation
- **State**: React hooks, React Hook Form for form state

## Code Quality
- **Linting**: ESLint with Next.js config
- **Testing**: Vitest with Testing Library
- **Formatting**: ESLint (likely with Prettier)
- **Type Checking**: TypeScript strict mode

## Database
- **ORM**: Prisma
- **Migrations**: Prisma Migrate
- **Schema**: Defined in `prisma/schema.prisma`
- **Seeding**: Prisma seed script

## File Organization
- Next.js App Router structure
- Components in appropriate directories
- API routes in `app/api/`
- Shared utilities in `lib/` or `utils/`
- Types in TypeScript files or dedicated type files

## Best Practices
- Use TypeScript for type safety
- Validate inputs with Zod
- Follow Next.js App Router conventions
- Use Prisma for database operations
- Implement proper error handling
- Use React Server Components where appropriate