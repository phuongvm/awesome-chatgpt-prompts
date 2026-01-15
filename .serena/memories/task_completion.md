# Task Completion Workflow for Awesome ChatGPT Prompts

## Before Completing a Task

### 1. Code Quality Checks
- [ ] TypeScript compiles without errors: `npm run build`
- [ ] Linting passes: `npm run lint`
- [ ] Tests pass: `npm test`
- [ ] Type safety verified (no `any` types unless necessary)

### 2. Database Changes
If database schema was modified:
- [ ] Prisma schema updated: `prisma/schema.prisma`
- [ ] Migration created: `npm run db:migrate`
- [ ] Prisma client regenerated: `npm run db:generate`
- [ ] Seed data updated if needed: `npm run db:seed`

### 3. Testing
- [ ] Unit tests written/updated
- [ ] Integration tests pass
- [ ] Manual testing completed
- [ ] Edge cases handled

### 4. Documentation
- [ ] README updated if needed
- [ ] Code comments added for complex logic
- [ ] API documentation updated (if applicable)

## Verification Checklist
- [ ] Build succeeds: `npm run build`
- [ ] All tests pass: `npm test`
- [ ] Linting clean: `npm run lint`
- [ ] Database migrations applied
- [ ] No console errors in development
- [ ] TypeScript types are correct

## Final Steps
1. Review `git status` and `git diff` to verify changes
2. Run full test suite: `npm test`
3. Build and verify: `npm run build`
4. Ask user: "Is this complete from your perspective? Any adjustments needed?"

## Important Reminders
- This is a Next.js application - follow App Router conventions
- Use Prisma for all database operations
- Validate inputs with Zod
- Follow TypeScript strict mode
- Test database migrations in development first
- Use React Server Components where appropriate