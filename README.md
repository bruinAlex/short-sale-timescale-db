# short-sale-timescale-db

# Installation Requirements
## Prereqs for Timescale DB
- Visual C++ Redistributable for Visual Studio 2015 (included in VS 2015 and later)
- A standard PostgreSQL 12 64-bit installation
- Make sure all relevant binaries are in your PATH: (use pg_config)
  - Windows: Add Postgres binary director to PATH (e.g. C:\Program Files\PostgreSQL\12\bin)
  - `pg_ctl --help` will be a useful command
## Install Timescale DB
- Go to https://docs.timescale.com/ for instructions
- Will need:
  - postgresql.conf path (e.g. C:\Program Files\PostgreSQL\12\data\postgresql.conf)
- Timescale will recommend settings based on hardware configuration

