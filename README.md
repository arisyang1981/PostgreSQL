# PostgreSQL

# vacuum full verbose
'vacuum full verbose' for all tables, triggered a bug, database offline, can't online. Bugs: \
https://github.com/timescale/timescaledb/issues/3924 \
Workaround: ignore system indexes, online database. \
https://www.postgresql.org/docs/current/runtime-config-developer.html \
