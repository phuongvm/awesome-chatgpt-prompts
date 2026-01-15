# Suggested Commands for Awesome ChatGPT Prompts

## Setup

### Quick Start (Recommended)
```bash
npx prompts.chat new my-prompt-library
cd my-prompt-library
```

### Manual Setup
```bash
git clone https://github.com/f/awesome-chatgpt-prompts.git
cd awesome-chatgpt-prompts
npm install
npm run setup
```

## Development

### Start Development Server
```bash
npm run dev
```

### Build for Production
```bash
npm run build
```

### Start Production Server
```bash
npm start
```

## Database

### Generate Prisma Client
```bash
npm run db:generate
```

### Run Migrations
```bash
npm run db:migrate        # Development migrations
npm run db:deploy         # Production migrations
npm run db:push           # Push schema changes (dev)
```

### Database Studio
```bash
npm run db:studio
```

### Seed Database
```bash
npm run db:seed
```

### Reset Admin
```bash
npm run db:resetadmin
```

### Full Database Setup
```bash
npm run db:setup
```

## Testing

### Run Tests
```bash
npm test                  # Run tests once
npm run test:watch        # Watch mode
npm run test:ui           # UI mode
npm run test:coverage     # With coverage
```

## Code Quality

### Linting
```bash
npm run lint
```

## Scripts

### Setup Wizard
```bash
npm run setup
```

### Generate Examples
```bash
npm run generate:examples
```

## Git Commands
```bash
git status                # Check repository status
git diff                  # Review changes
git log -n 5              # Review recent commits
```

## Windows-Specific Commands
- Use `dir` instead of `ls`
- Use `cd` for directory navigation
- Use PowerShell or Git Bash
- Paths use backslashes: `O:\workspaces\oss\awesome-chatgpt-prompts`