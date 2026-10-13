# nflverse

The nflverse is a set of packages dedicated to data and analysis of the National Football League. 

Most data is stored in releases of the [nflverse/nflverse-data](https://github.com/nflverse/nflverse-data) repository, in various formats (e.g. csv, parquet, and rds). 

These can be accessed by any platform or programming language via the web URLs. We also maintain a set of packages to facilitate access to this data and apply modelling.

## R Packages

- [`{nflverse}`](https://github.com/nflverse/nflverse) helps install and update all nflverse R packages.
- [`{nflreadr}`](https://github.com/nflverse/nflreadr) provides easy access to nflverse data repositories.
- [`{nflfastR}`](https://github.com/nflverse/nflfastR) cleans play by play data and applies EPA/WPA modelling.
  - Most users will want precomputed data, via `nflreadr`.
- [`{nflplotR}`](https://github.com/nflverse/nflplotR) facilitates plotting NFL data.
- [`{nfl4th}`](https://github.com/nflverse/nfl4th) studies fourth down decisions with nflverse data and models.
- [`{nflseedR}`](https://github.com/nflverse/nflseedr) simulates NFL season schedules with the user's model.

## Python Packages
- [`nflreadpy`](https://github.com/nflverse/nflreadpy) ports nflreadr to Python and provides easy, lightweight access to nflverse data repositories.

## Julia Packages
- [`NFLData.jl`](https://github.com/nflverse/NFLData.jl) provides easy access to nflverse data repositories in Julia.

# Support

In most cases you should reach out to us on Discord: 

[![nflverse
support](https://img.shields.io/discord/789805604076126219?color=7289da&label=nflverse%20support&logo=discord&logoColor=fff&style=flat-square)](https://discord.com/invite/5Er2FBnnQa)

# Licensing

The majority of all nflverse data available (ie all data stored in nflverse/nflverse-data releases EXCEPT the FTN data as of October 2026) is broadly licensed as [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/), and the FTN data is licensed as [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Any datasets with specific licenses will be marked in the corresponding nflverse/nflverse-data release page as well the nflreadr/nflreadpy/nfldata.jl package documentation. 

From the nflverse's perspective, CC-BY 4.0 loosely means anyone is permitted to use any of the CC-BY 4.0 datasets for both non-commercial and commercial purposes provided that you attribute the nflverse and (if applicable) the provider nflverse sourced it from. CC-BY-SA (currently primarily used by FTN-provided datasets) means that anything derived from the data (models, applications, etc) must also be provided under the same terms (i.e. open-source and for free). CC-BY-SA-NC explicitly prohibits commercial usage (this license is not used by any of the nflverse datasets as of October 2026).

There has been a recent influx of (LLM-generated) inquiries by email, github issues, and discord messages about the licensing of data, most of them asking about permission to use the data commercially. The nflverse's CC licenses, along with fair use exceptions, are sufficient for most non-commercial projects. The nflverse itself does not care if you want to use our datasets in commercial projects, as long as the attribution and share-alike clauses are respected, but does not provide any warranty or bear any legal responsibility for how you use the data in commercial projects. If you are worried about potential legal issues stemming from your commercial use of the data, you should consult a lawyer. 

We will ignore any further inquiries on the topic of licensing.
