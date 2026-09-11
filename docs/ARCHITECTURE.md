# Architecture — Template

Starter for Paper plugins with DB and commands.

```
Paper 1.26.2
  └─ TemplatePlugin
       ├─ Database — HikariCP (sqlite/mysql/pg)
       ├─ PingHistoryRepository / PlayerDataRepository — example DAOs
       ├─ PlayerJoinListener — async upsert
       └─ PingCommand — /ping with tab-complete
```

Use as base: rename package `com.example.template` → yours, update `plugin.yml` name/main, slim deps if needed.
