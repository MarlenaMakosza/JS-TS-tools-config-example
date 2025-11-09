# JS/TS tools config example
Simple setup with needed by me (possibly in the future for all popular tools) plugins/tools. Everything in one file, just copy paste to your project.

Flat eslint setup plugins that can be turned on and off. If you need only eslint config -> [here](https://github.com/Lenerystia/eslint-ultimate-config)

This project only contains example configuration files - it is not a project for coding.

# Included Tools
- **[ESLint](https://eslint.org/)**: For linting JavaScript and TypeScript.
- **[Prettier](https://prettier.io/)**: For code formatting.
- **[Husky](https://typicode.github.io/husky/)**: To run Git hooks.
- **[lint-staged](https://github.com/okonet/lint-staged)**: To lint files before committing.
- **[Stylelint](https://stylelint.io/)**: For linting CSS/SCSS.
- **[CSpell](https://github.com/streetsidesoftware/cspell)**: Spell Checker for Code.
- **[Commitlint](https://commitlint.js.org/)**: To enforce conventional commit messages.
- **[NPM check updates](https://www.npmjs.com/package/npm-check-updates)**: For updating your package.json dependencies to the latest versions.
- **[HTTP Status Codes](https://www.npmjs.com/package/http-status-codes)**: Constants enumerating the HTTP status codes.

And a few others, but I haven't set them up or documented them here yet, even though they're listed in package.json.

"svelte-check": "^4.1.0",
"vitest": "^2.0.4",
"@types/d3-graphviz": "^2.6.10",
"drizzle-kit": "^0.22.0",
"@faker-js/faker": "^9.3.0",
"drizzle-orm": "^0.31.2",

# Installation
## Tools
### For Windows (if you want other look in source)
```
npm install --save-dev eslint typescript prettier husky lint-staged cspell commitlint @commitlint/cli @commitlint/config-conventional commitlint-plugin-function-rules npm-check-updates stylelint stylelint-config-standard http-status-codes
```

## [Eslint plugins](https://github.com/Lenerystia/eslint-ultimate-config) <- (If you want list of all plugins, go here)
```
npm install --save-dev @eslint/js typescript-eslint typescript svelte-eslint-parser eslint-plugin-svelte prettier-plugin-svelte @html-eslint/parser @html-eslint/eslint-plugin eslint-plugin-tailwindcss @pandacss/eslint-plugin eslint-plugin-drizzle @vitest/eslint-plugin eslint-plugin-perfectionist eslint-plugin-unicorn @stylistic/eslint-plugin eslint-plugin-functional eslint-config-prettier prettier-plugin-organize-imports eslint-plugin-security eslint-plugin-sonarjs eslint-plugin-tsdoc eslint-plugin-promise @cspell/eslint-plugin eslint-plugin-import eslint-plugin-import-alias eslint-plugin-eslint-plugin 
```

## 👩‍💻 Author

Made by [Marlena Makosza](https://marlenamakosza.com)
