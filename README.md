dasset
======

Lightweight Asset Management for Dell Hardware

```
usage: dasset [-h] [--json] [--csv] [--update] [--skip] [--remove] [--eol]
              [--exp EXP] [--printall]
              [stags [stags ...]]

Lightweight Dell Hardware Asset Management

positional arguments:
  stags

optional arguments:
  -h, --help  show this help message and exit
  --json      Output results as JSON.
  --csv       Output results as CSV.
  --update    Update DB with results from Dell.
  --skip      Skip local DB check and always poll Dell for data.
  --remove    Remove STAG from local DB.
  --eol       Toggle EOL status of given STAG.
  --exp EXP   Show hardware which has <= N remaining days of warranty.
  --printall  Print everything we have in the DB.
```