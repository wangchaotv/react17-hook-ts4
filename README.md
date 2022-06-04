# 环境变量

- 运行 npm start 时，读取 .env.development
- 运行 npm run build 时，读取 .env
- 读取解析后，挂载到 process.env，例如：process.env.REACT_APP_API_URL
