# nflverse

The nflverse is a set of packages dedicated to data and analysis of the National Football League.

Most data is stored in releases of the [nflverse/nflverse-data](https://github.com/nflverse/nflverse-data) repository, in various formats (csv, parquet, rds, qs being the primary ones). 

## R Packages

- [`{nflverse}`](https://github.com/nflverse/nflverse) helps install and update all nflverse R packages.
- [`{nflreadr}`](https://github.com/nflverse/nflreadr) provides easy access to nflverse data repositories.
- [`{nflfastR}`](https://github.com/nflverse/nflfastR) cleans play by play data and applies EPA/WPA modelling. Most users will want precomputed data, via `nflreadr`.
- [`{nflplotR}`](https://github.com/nflverse/nflplotR) facilitates plotting NFL data.
- [`{nfl4th}`](https://github.com/nflverse/nfl4th) studies fourth down decisions with nflverse data and models.
- [`{nflseedR}`](https://github.com/nflverse/nflseedr) simulates NFL season schedules with the user's model.
