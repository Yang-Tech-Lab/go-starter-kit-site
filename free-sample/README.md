# Go Starter Kit — Free Sample: 12 SQL Exercises

A free sample from the [Go Starter Kit](https://yang-tech-lab.github.io/go-starter-kit-site/) — twelve progressive SQL exercises on the starter's own schema (the same `users`, `links`, and `notes` tables the API uses). They cover the SQL you will actually write while building on the starter: filtering, joins, aggregation, subqueries, and window functions.

## What's in this sample

- `EXERCISES.md` — the exercise list, setup instructions, and tips
- `seed.sql` — creates the tables and inserts sample data (4 users, 5 links, 6 notes)
- `exercises.sql` — the 12 exercise prompts, ready for your queries
- `solutions.sql` — reference answers (try first, then check)

## How to use it

You need SQLite. With the `sqlite3` command-line tool:

```bash
sqlite3 exercises.db < seed.sql
sqlite3 exercises.db
# then work through exercises.sql, one query at a time
```

Without the CLI, open the files in DB Browser for SQLite (free, sqlitebrowser.org) and run `seed.sql` there. See `EXERCISES.md` for the full guide.

## The full kit

This sample is one small piece of the Go Starter Kit — a production-shaped Go REST API starter in pure stdlib Go:

- Full Go source code — API, JWT auth, SQLite store, migrations, tests
- Two working example apps: shortlinks + notes
- Four guides: architecture, auth, database, deployment
- These 12 SQL exercises with solutions
- Dockerfile and Makefile included

$19 one-time: https://yang-tech-lab.github.io/go-starter-kit-site/

## License

This sample is free for personal learning. Please don't redistribute it or the full starter kit — if you know someone who'd like it, send them to the store page above. Questions: yanglao290@gmail.com.
