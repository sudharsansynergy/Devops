# MongoDB Connections

> **Note:** Passwords have been replaced with `xxxx` for security purposes.

## Databases (sorted by authSource)

### beta-syia-api

```bash
mongodb://beta-syia:xxxx@13.202.145.171:27017/?authSource=beta-syia-api
#DB : beta-syia-api 
#Instance : Siya MongoDB Prod 
```

### syia-etl

```bash
mongodb://etl:xxxx@db.syia.ai:27017/?authMechanism=SCRAM-SHA-1&authSource=syia-etl
#DB : etl
#Instance : Siya MongoDB ETL DATA
```

### syia-etl-dev

```bash
mongodb://user:xxxx@db.syia.ai:27017/?authMechanism=SCRAM-SHA-1&authSource=syia-etl-dev
mongodb://prasanna.p:xxxx@db.syia.ai:27017/?authMechanism=SCRAM-SHA-1&authSource=syia-etl-dev
mongodb://sabareesh:xxxx@db.syia.ai:27017/?authSource=syia-etl-dev
#DB : syia-etl
#Instance : Siya MongoDB ETL DATA
```

### syia-etl-prod

```bash
mongodb://syia-etl-prod:xxxx@db-etl.prod.syia.ai:27017/?authSource=syia-etl-prod
#DB : syia-etl-prod
#Instance : Syia MongoDB ETL
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
