# Modified Snippets for Obsidian Latex Suite
https://github.com/artisticat1/obsidian-latex-suite provides **snippets** for
faster LaTeX writing!

The snippets themselves are a entries in a TypeScript file:
```typescript
{trigger: string, replacement: string, options: string, description?: string, priority?: number}
```

```typescript
export const DEFAULT_SNIPPETS_ARR = [
  // ...
  {trigger: "mk", replacement: "$$0$", options: "tA"}
  // ...
]
```
See https://github.com/artisticat1/obsidian-latex-suite#snippets for more
detail.

# Usage
Personally, I symlink the `snippets.ts` file in my Obsidian vault using
`ln -sf /path/to/snippets.ts .`

The downside to this is that any updates to the `snippets.ts` file must be
symlinked again, which is kind of annoying.

