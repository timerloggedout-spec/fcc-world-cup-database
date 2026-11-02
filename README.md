# Build a World Cup Database

FreeCodeCamp Relational Databases v9 certification project (unit 039).

- `worldcup.sql` — recreates the `worldcup` database structure (teams, games).
- `insert_data.sh` — loads `games.csv` into the database (24 teams, 32 games).
- `queries.sh` — statistics queries; output matches the course `expected_output.txt` exactly.

Built as a fleet run in timerloggedout-spec/termux-monorepo (`cert-project.yml` run 41379161305, fileset mode):
structure stories verified in-run, counts verified in both `worldcup` and `worldcuptest`, queries output diffed exactly.
