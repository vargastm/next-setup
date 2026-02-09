# Next.js Setup

Base setup to start Next.js projects with TypeScript, Tailwind CSS and ESLint configured.

## 🚀 Included Technologies

- **Next.js 16.1.1** - React framework for production
- **TypeScript 5** - Static typing
- **Tailwind CSS 4** - Utility-first CSS framework
- **ESLint 9** - Linter for JavaScript/TypeScript
- **Prettier** - Code formatter

## 📦 Installation

To use this setup in a new project:

```bash
# Copy configuration files to your new project
# or use this directory as a base

# Install dependencies
pnpm install
```

## 🛠️ Available Commands

```bash
# Development
pnpm run dev

# Build for production
pnpm run build

# Start production server
pnpm start

# Check lint errors
pnpm run lint

# Fix lint errors automatically
pnpm run lint:fix
```

## 📁 Setup Structure

### Configuration Files

- **`package.json`** - Project dependencies and scripts
- **`tsconfig.json`** - TypeScript configuration
- **`next.config.ts`** - Next.js configuration
- **`eslint.config.mjs`** - ESLint configuration
- **`postcss.config.mjs`** - PostCSS configuration for Tailwind
- **`.prettierrc`** - Prettier configuration
- **`.gitignore`** - Files ignored by Git

### Folder Structure

```
next-setup/
├── app/
│   ├── globals.css      # Global styles with Tailwind
│   ├── layout.tsx       # Root layout
│   └── page.tsx         # Home page
├── package.json
├── tsconfig.json
├── next.config.ts
├── eslint.config.mjs
├── postcss.config.mjs
└── .prettierrc
```

## ⚙️ ESLint Configuration

ESLint is configured with:

- **TypeScript ESLint** - Rules for TypeScript
- **React** - Rules for React
- **JSX A11y** - Accessibility rules
- **Prettier** - Prettier integration
- **Simple Import Sort** - Automatic import sorting

### Main Rules

- Unused variables with `_` prefix are ignored
- Imports are automatically sorted
- Prettier integrated as ESLint rule
- React doesn't need import in JSX scope

## 🎨 Prettier Configuration

- **printWidth**: 80 characters
- **tabWidth**: 2 spaces
- **singleQuote**: true
- **trailingComma**: 'all'
- **semi**: false
- **arrowParens**: 'always'
- Tailwind CSS plugin to sort classes

## 📝 TypeScript

Configured with:
- Strict mode enabled
- Path aliases (`@/*` points to project root)
- React JSX support
- Incremental builds enabled

## 🎯 How to Use

1. Copy configuration files to your new project
2. Run `pnpm install` to install dependencies
3. Start developing!

## 📄 License

See the [LICENSE](LICENSE) file for more information.
