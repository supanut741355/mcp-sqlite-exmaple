### Steps

### 1.Install sqlite if not exist
```
brew install sqlite
```

### 2. Run init.sql script

### 3. Open sql-client to check (select path to test.db file) and try query
```
select name, price from products;
```

### 4. Implement mcp client (this example use Claude)

```
code /user/<USER_NAME>/Library/Application Support/Claude/claude_desktop_config.json
```

### 5. Check status of sqlite mcp at Claude's setting > Developer

### 6. If status = "running", try prompt 
```
Pls, list all products
```