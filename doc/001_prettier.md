```bash
npm i --exact -D prettier

echo {} > .prettierrc.json
echo '' > .prettierignore

prettier --write .
```

```bash
## 解决 prettier 和 eslint 的冲突
# 用 prettier 的规则覆盖一部 eslint 的规则
npm i -D eslint-config-prettier
```
