# pghero.sh

> Shell script wrapper for [PgHero](https://github.com/ankane/pghero)

```
$ pghero help

USAGE:

  pghero [COMMAND] [SUBCOMMAND] [PSQL OPTIONS]... 

COMMANDS:

  help      - Show this help text
  space     - Show largest tables and indexes
  install   - Install pghero
  uninstall - Uninstall pghero

  query:
    all     - View all running queries
    long    - Queries running for longer than five minutes
    kill    - Kill query by pid
    killall - Kill all queries

  index:
    usage   - Show general usage
    missing - Missing indexes
    unused  - Unused indexed

  cache:
    index   - Index hit rate
    table   - Table hit rate

Note: all additional parameters are passed on to psql

EXAMPLES:

  > pghero install -W
  > pghero query all
  > pghero space -d <database> -U <user>

```

