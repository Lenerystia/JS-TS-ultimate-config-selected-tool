# JS/TS ultimate config - selected tools
Simple setup with needed by me (possibly in the future for all popular tools) plugins/tools. Everything in one file, just copy paste to your project.

Flat eslint setup plugins that can be turned on and off.

This project is only example config files - there are not project to coding.

# Included Tools
- **[ESLint](https://eslint.org/)**: For linting JavaScript and TypeScript.
- **[Prettier](https://prettier.io/)**: For code formatting.
- **[Husky](https://typicode.github.io/husky/)**: To run Git hooks.
- **[lint-staged](https://github.com/okonet/lint-staged)**: To lint files before committing.
- **[Stylelint](https://stylelint.io/)** (optional): For linting CSS/SCSS.
- **[CSpell](https://github.com/streetsidesoftware/cspell)**: Spell Checker for Code.
- **[Commitlint](https://commitlint.js.org/)**: To enforce conventional commit messages.

# Installation
## Tools
### For Windows (if you want other look in source)
```
npm install --save-dev eslint typescript prettier husky lint-staged cspell commitlint @commitlint/cli @commitlint/config-conventional
```

## Eslint plugins
### [Eslint JS](https://eslint.org/)
```
npm install --save-dev @eslint/js
```

### [Eslint TypeScript](https://typescript-eslint.io/)
```
npm install --save-dev typescript-eslint typescript
```

### [Svelte](https://github.com/sveltejs/eslint-plugin-svelte)
For linting and formatting Svelte files. Includes:
- **[Svelte ESLint Parser](https://github.com/sveltejs/svelte-eslint-parser)**: Parses `.svelte` files for ESLint.
- **[ESLint Plugin Svelte](https://github.com/sveltejs/eslint-plugin-svelte)**: Provides linting rules specific to Svelte.
- **[Prettier Plugin Svelte](https://github.com/sveltejs/prettier-plugin-svelte)**: Enables Prettier to format Svelte files.
```
npm install --save-dev svelte-eslint-parser eslint-plugin-svelte prettier-plugin-svelte
```

### [HTML](https://html-eslint.org/)
```
npm install --save-dev @html-eslint/parser @html-eslint/eslint-plugin
```

### [Tailwind CSS](https://www.npmjs.com/package/eslint-plugin-tailwindcss)
```
npm install --save-dev eslint-plugin-tailwindcss
```

### [PandaCSS](https://github.com/chakra-ui/eslint-plugin-panda)
```
npm install --save-dev  @pandacss/eslint-plugin
```

### [Drizzle ORM](https://orm.drizzle.team/docs/eslint-plugin)
```
npm install --save-dev eslint-plugin-drizzle
```

### [Vitest](https://github.com/vitest-dev/eslint-plugin-vitest)
```
npm install --save-dev @vitest/eslint-plugin
```
### Style & Best Practices
For maintaining clean and organized code. Includes:
- **[Perfectionist](https://perfectionist.dev/)**: Ensures consistent ordering in objects and imports.
- **[Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)**: Enforces good practices.
- **[Stylistic](https://eslint.style/packages/default)**: Style-based rules for ESLint.
- **[Functional](https://github.com/eslint-functional/eslint-plugin-functional)**: Enforces functional programming principles.
- **[Prettier](https://prettier.io/docs/en/integrating-with-linters.html)**: Code formatting.
- **[Prettier-Organize-Imports](https://github.com/simonhaenisch/prettier-plugin-organize-imports)**: Automatically organizes imports.

```
npm install --save-dev eslint-plugin-perfectionist eslint-plugin-unicorn @stylistic/eslint-plugin eslint-plugin-functional eslint-config-prettier prettier-plugin-organize-imports
```

### Security & Quality
For improving code security and quality. Includes:
- **[ESLint Security](https://github.com/nodesecurity/eslint-plugin-security)**: Identifies potential security vulnerabilities in your code.
- **[SonarJS](https://www.npmjs.com/package/eslint-plugin-sonarjs)**: Detects bugs and code smells.
- **[TSDoc](https://tsdoc.org/pages/packages/eslint-plugin-tsdoc/)**: Enforces consistent and valid TypeScript documentation comments.
- **[ESLint Promise](https://github.com/xjamundx/eslint-plugin-promise)**: Ensures best practices for working with JavaScript Promises.
- **[CSpell](https://github.com/streetsidesoftware/cspell/tree/main/packages/cspell-eslint-plugin)**: Spell Checker for code comments, strings, and identifiers.

```
npm install --save-dev eslint-plugin-security eslint-plugin-sonarjs eslint-plugin-tsdoc eslint-plugin-promise @cspell/eslint-plugin
```

### Import Management
For managing and organizing imports effectively. Includes:
- **[ESLint Plugin Import](https://github.com/import-js/eslint-plugin-import)**: Helps validate proper imports and exports, enforces consistent style, and prevents import errors.
- **[ESLint Plugin Import Alias](https://www.npmjs.com/package/eslint-plugin-import-alias)**: Simplifies working with path aliases in your project.

```
npm install --save-dev eslint-plugin-import eslint-plugin-import-alias
```

### [Meta Plugins](https://www.npmjs.com/package/eslint-plugin-eslint-plugin)
```
npm install --save-dev eslint-plugin-eslint-plugin
```

## [Stylelint](https://stylelint.io/)
```
npm install --save-dev stylelint stylelint-config-standard
```
