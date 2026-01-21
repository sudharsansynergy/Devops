# MongoDB Connections

> **Note:** Passwords have been replaced with `xxxx` for security purposes.

## Databases (sorted by authSource)

### beta-syia-api

```bash
mongodb://beta-syia:xxxx@13.202.145.171:27017/?authSource=beta-syia-api
```

### one-sea-etl

```bash
mongodb://one-sea-etl:xxxx@13.126.193.146:27017/?authSource=one-sea-etl
```

### spar

```bash
mongodb://spar:xxxx@3.111.130.25:27017/?authSource=spar
```

### Synergy

```bash
mongodb://Synergy:xxxx@13.126.193.146:27017/?authSource=Synergy&authMechanism=SCRAM-SHA-1
```

### Synergy-etl

```bash
mongodb://Synergy-etl:xxxx@13.126.193.146:27017/?authSource=Synergy-etl
```

### syia-etl

```bash
mongodb://etl:xxxx@db.syia.ai:27017/?authMechanism=SCRAM-SHA-1&authSource=syia-etl
```

### syia-etl-dev

```bash
mongodb://user:xxxx@db.syia.ai:27017/?authMechanism=SCRAM-SHA-1&authSource=syia-etl-dev
mongodb://prasanna.p:xxxx@db.syia.ai:27017/?authMechanism=SCRAM-SHA-1&authSource=syia-etl-dev
mongodb://sabareesh:xxxx@db.syia.ai:27017/?authSource=syia-etl-dev
```

### syia-etl-prod

```bash
mongodb://syia-etl-prod:xxxx@db-etl.prod.syia.ai:27017/?authSource=syia-etl-prod
```

---

## Quick Reference Table

| authSource | Host | Port | User |
|------------|------|------|------|
| beta-syia-api | 13.202.145.171 | 27017 | beta-syia |
| one-sea-etl | 13.126.193.146 | 27017 | one-sea-etl |
| spar | 3.111.130.25 | 27017 | spar |
| Synergy | 13.126.193.146 | 27017 | Synergy |
| Synergy-etl | 13.126.193.146 | 27017 | Synergy-etl |
| syia-etl | db.syia.ai | 27017 | etl |
| syia-etl-dev | db.syia.ai | 27017 | user, prasanna.p, sabareesh |
| syia-etl-prod | db-etl.prod.syia.ai | 27017 | syia-etl-prod |
