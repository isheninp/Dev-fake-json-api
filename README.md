# Simple development fake api
Thanks to https://github.com/typicode/json-server

```
npm install json-server
```

db.json
```
{
    "json": [
      {
        "key": "value"
      }
    ]
  }
```

# Linux
```
json-server -p 3001 --watch db.json
```

# Windows
```
node node_modules/json-server/lib/cli/bin.js -p 3001 --watch db.json
```