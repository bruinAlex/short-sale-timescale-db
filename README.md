# short-sale-timescale-db

# Windows Installation Requirements and Process
## Prereqs for Timescale DB
- Visual C++ Redistributable for Visual Studio 2015 (included in VS 2015 and later)
- A standard PostgreSQL 12 64-bit installation
- Make sure all relevant binaries are in your PATH: (use pg_config)
  - Add Postgres binary director to PATH (e.g. C:\Program Files\PostgreSQL\12\bin)
  - Add `PGDATA` as environment variable and set to a directory where the database data will be stored (e.g. C:\Program Files\PostgreSQL\12\data)
  - `pg_ctl --help` will be a useful command
## Install Timescale DB
- Go to https://docs.timescale.com/ for instructions
- Will need:
  - postgresql.conf path (e.g. C:\Program Files\PostgreSQL\12\data\postgresql.conf)
- Timescale will recommend settings based on hardware configuration
