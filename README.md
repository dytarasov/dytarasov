### Dmitriy Tarasov

Software developer. Currently ML/AI engineering: LLM agents, RAG, tool calling. Also PostgreSQL and networking.

---

**[ftybucks](https://github.com/dytarasov/ftybucks-public)**: VPN tunnel disguised as PostgreSQL streaming replication. PG wire handshake, libpq TLS fingerprint (uTLS), traffic in `CopyData` frames, X25519 + ChaCha20-Poly1305. Gateway mode: WireGuard ingress, GeoIP split routing, ECMP across N tunnels with failover. Go.

**[claudetelegram](https://github.com/dytarasov/claudetelegram)**: Telegram interface to a persistent Claude Code session. Self-modifying: preflight checks, commit, restart. An external watchdog rolls back to the last stable revision on a failed health check. Python, aiogram, dishka.

**[jevchess](https://github.com/dytarasov/jevchess)**: chess engine driven by the Jev decision model. Supports human vs. model and Stockfish vs. model. Python, python-chess.

Private:
- **Analyst Oslik**: text-to-SQL/report over ClickHouse. ReAct agent, retrieval over a PostgreSQL semantic layer, Neo4j and pgvector; guarded SQL execution; SSE streaming.
- **[FastRide](https://frmoto.ru)**: rental platform in production. FastAPI, asyncpg, PostgreSQL 16, React, MinIO, Nginx.

---

Python · Go · PostgreSQL · FastAPI · Docker · Linux · ClickHouse · Neo4j · pgvector
