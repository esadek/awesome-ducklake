# Awesome DuckLake

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [DuckLake](https://ducklake.select/) tools and
resources.

## Contents

- [Interfaces](#interfaces)
- [Libraries](#libraries)
- [Transformation](#transformation)
- [Implementations](#implementations)
- [Resources](#resources)
  - [Documentation](#documentation)
  - [Examples](#examples)
  - [Videos](#videos)
  - [Presentations](#presentations)

## Interfaces

- [DBeaver](https://dbeaver.io/) - Universal database tool and SQL client
- [DuckDB CLI](https://duckdb.org/docs/stable/clients/cli/overview.html) -
  DuckDB command-line interface
- [DuckDB UI Extension](https://duckdb.org/docs/stable/core_extensions/ui.html) -
  A user interface for your local DuckDB instance
- [Harlequin](https://harlequin.sh/) - The SQL IDE for your terminal
- [marimo](https://marimo.io/) - Reactive Python notebook
- [Positron](https://positron.posit.co/) - A next-generation data science IDE
- [Sling](https://docs.slingdata.io/) - Efficient data transfer between various
  sources and destinations

## Libraries

- [dlt](https://dlthub.com/) - Python library that loads data from various data
  sources into well-structured, live datasets
- [Ibis](https://ibis-project.org/) - Portable Python dataframe library
- [Narwhals](https://narwhals-dev.github.io/narwhals/) - Lightweight and
  extensible compatibility layer between dataframe libraries
- [Pointblank](https://posit-dev.github.io/pointblank/) - Powerful, yet elegant
  data validation framework for Python
- [PySpark](https://spark.apache.org/docs/latest/api/python/index.html) - Python
  API for Apache Spark

## Transformation

- [dbt Core](https://docs.getdbt.com/docs/core/connect-data-platform/duckdb-setup) -
  Open-source tool that enables transformation using analytics engineering best
  practices
- [lea](https://github.com/carbonfact/lea) - Minimalist SQL orchestrator
- [SQLMesh](https://www.tobikodata.com/sqlmesh) - Scalable and efficient data
  transformation framework

## Implementations

- [DuckDB](https://duckdb.org/docs/stable/core_extensions/ducklake) - DuckDB
  core extension for attaching to databases stored in the DuckLake format
- [MotherDuck](https://motherduck.com/blog/announcing-ducklake-support-motherduck-preview/) -
  Cloud data warehouse with support for managed DuckLake

## Resources

### Documentation

- [DuckLake DuckDB extension](https://ducklake.select/docs/stable/duckdb/introduction.html) -
  Documentation for the `ducklake` DuckDB extension
- [Manifesto](https://ducklake.select/manifesto/) - The DuckLake manifesto from
  Mark Raasveldt and Hannes Mühleisen
- [Specification](https://ducklake.select/docs/stable/specification/introduction.html) -
  The specification for the DuckLake format

### Examples

- [DuckDB Python API](https://github.com/esadek/ducklake-examples/blob/main/examples/duckdb.ipynb) -
  Python notebook demonstrating usage of the DuckDB Python API
- [Ibis](https://github.com/esadek/ducklake-examples/blob/main/examples/ibis.ipynb) -
  Python notebook demonstrating usage of the Ibis dataframe library
- [Pointblank](https://github.com/esadek/ducklake-examples/blob/main/examples/pointblank.ipynb) -
  Python notebook demonstrating usage of the Pointblank data validation
  framework
- [PySpark](https://github.com/esadek/ducklake-examples/blob/main/examples/pyspark.ipynb) -
  Python notebook demonstrating usage of PySpark
- [DuckLake + SQLMesh Tutorial: Build a Modern Data Lakehouse On Your Laptop](https://www.tobikodata.com/blog/ducklake-sqlmesh-tutorial-a-hands-on) - tutorial for settin up a local DuckLake with SQLMesh.

### Videos

- [DuckLake & The Future of Open Table Formats](https://www.youtube.com/watch?v=yn07s-_PgrI) -
  An in-depth discussion about DuckLake with Jordan Tigani and Hannes Mühleisen
- [DuckLake - The SQL-Powered Lakehouse Format for the Rest of Us](https://www.youtube.com/watch?v=YQEUkFWa69o) -
  A talk on the design rationale and principles of DuckLake by Hannes Mühleisen
- [DuckLake: Learning from Cloud Data Warehouses to Build a Robust “Lakehouse”](https://www.youtube.com/watch?v=z2GhznqtIz0) -
  A seminar by Jordan Tigani
- [Introducing DuckLake](https://www.youtube.com/watch?v=zeonmOO9jm4) - A
  podcast on the DuckLake project by Hannes Mühleisen and Mark Raasveldt

### Presentations

- [DuckLake: The SQL-Powered Lakehouse Format](https://blobs.duckdb.org/slides/hannes-muehleisen-ducklake-open-lakehouse-meetup.pdf) -
  Presentation by Hannes Mühleisen

### DuckLake Setups

- [DuckLake on Hetzner](https://github.com/berndsen-io/ducklake-hetzner)
- [DuckLake on Leafcloud](https://szarnyasg.org/posts/ducklake-on-leafcloud/)
