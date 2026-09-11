# Configuration — Template

`plugins/TemplatePlugin/config.yml`:

```yaml
database:
  type: sqlite
  pool: { maximum-pool-size: 10 }
  sqlite: { file: database.db }
ping:
  save-history: true
```

Switch DB → restart. See `docker-compose.yml` for mysql/pg testing.
