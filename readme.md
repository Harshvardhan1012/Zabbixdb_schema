# Zabbix DB

This project contains scripts and instructions to manage the Zabbix database.

## Installation

First, install the `dbdocs` tool globally:

```bash
npm install -g dbdocs
```

## Usage

Convert the PostgreSQL schema to DBML format:

```bash
dbdocs db2dbml postgres schema.sql -o database.dbml
```

Log in to `dbdocs`:

```bash
dbdocs login
```

Build the project on `dbdocs`:

```bash
dbdocs build database.dbml --project Ecommerce
```


