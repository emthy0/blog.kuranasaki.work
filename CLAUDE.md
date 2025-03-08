# Fuwari Blog Development Guidelines

## Commands
- `pnpm dev` - Start development server
- `pnpm build` - Build for production (Astro build + Pagefind)
- `pnpm lint` - Run Biome linter
- `pnpm format` - Run Biome formatter
- `pnpm type-check` - Run TypeScript checks
- `pnpm new-post <filename>` - Create a new blog post

## Code Style
- Use Biome for formatting/linting
- 2-space indentation, 80 character line width
- Single quotes for JS/JSX, trailing commas, optional semicolons
- Organized imports (enabled by default)
- Follow accessible, correct, and secure coding practices
- Use path aliases (@components, @utils, etc.) for imports
- Use TypeScript with strict null checks

## Project Structure
- Content in `src/content/posts/`
- Components in `src/components/`
- Page templates in `src/pages/`
- Config in `src/config.ts`
- i18n support via `src/i18n/`
- Use Svelte for interactive components, Astro for static ones
- Follow existing patterns for new components