```bash
npm i -D @commit/{config-conventional,cli}

echo 'module.exports = { extends: ["@commitlint/config-conventional"] };' > commitlint.config.js

npx husky add .husky/commit-msg "npx commitlint --edit $1"
```
