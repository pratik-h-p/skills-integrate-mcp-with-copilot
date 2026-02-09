# Add persistent storage (database) for activities and students

Description
-----------
Replace the in-memory data store with a database backend (SQLite for dev, Postgres for production). Migrate activity and student models to persistent tables, add a simple data access layer (ORM or raw queries), and update API endpoints to read/write from the DB.

Acceptance criteria
-------------------
- Data persists across server restarts.
- CRUD operations for activities and students work through the API.
- A simple migration or initialization path is included.

Labels: backend, enhancement
