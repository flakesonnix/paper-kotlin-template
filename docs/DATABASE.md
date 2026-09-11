# Database — Template

HikariCP wrapper in `db/Database` — handles sqlite/mysql/postgresql URL + driver. `migrate()` does `CREATE TABLE IF NOT EXISTS` for example tables.

Example DAOs show pattern for save/recent/average and upsert. Copy pattern for your tables.
