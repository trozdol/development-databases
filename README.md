## Development Databases:

Database images chosen based on it working for an M1 Mac. If you have Docker installed run...

    docker-compose up

Database info is in `docker-compose.yml` but using all default ports.


| FLAVOR     | PORT  | DATABASE | USER    | PASSWORD          |
|------------|-------|----------|---------|-------------------|
| MySQL      | 3306  | example  | example | secretPassword!@# |
| Redis      | 5432  | ?        | ?       |                   |
| Postgres   | 27017 | ?        | example | secretPassword!@# |
| MongoDB    | 6379  | ?        | example | secretPassword!@# |
| SQL Server | 1433  | ?        | SA      | secretPassword!@# |

TODO:
- make sure each has database schema with the same name, user and password.
- demo data scripts.