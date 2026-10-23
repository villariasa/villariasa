# added error handling on mysql connection drop

- Repo: villariasa/villariasa
- Date: 2026-10-23T00:39:49.963Z
- PR: adjust database connector factory connection pool
- Details: catch broken pipes and attempt clean reconnect
