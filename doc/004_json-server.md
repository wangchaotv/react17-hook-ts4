```bash
npm i -D json-server

mkdir **json_server_mock** && cd **json_server_mock** && echo {} > db.json
```

```json
# npm scripts
{
    "json-server": "json-server __json_server_mock__/db.json --watch"
}
```
