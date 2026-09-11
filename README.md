# Paper Kotlin Template

Paper 1.26.2 — Kotlin 2.0.21 — Java 21. Minimal starter for Paper plugins.

Comes with HikariCP (sqlite/mysql/pg), Spotless/ktlint, nixfmt, IDEA run configs, and a Nix flake. Build gives a fat jar via `shadowJar`.

```bash
nix develop
gradle shadowJar
# → build/libs/template-plugin-1.0.0.jar
```

## What's inside

- `/ping` command (perm `template.ping`, async DB save)
- `Database` wrapper + `PingHistoryRepository` / `PlayerDataRepository`
- `flake.nix` with `jdk21`, `gradle_8`, `jetbrains.idea`, `nixfmt`, `ktlint`

## Use this template

Click **Use this template** on GitHub, or:

```bash
gh repo create my-plugin --template flakesonnix/paper-kotlin-template --public --clone
nix develop -c gradle shadowJar
```

Paper & Spigot compatible. See `docs/` for getting started, DB, and dev.
