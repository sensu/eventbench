> [!WARNING]
> **This repository is scheduled to be archived on 13th November 2026.**
>
> After that date it will be read-only: no new commits, issues, or pull requests, and no further maintenance or security updates will be issued.

This is a tool for benchmarking postgresql with the access pattern that Sensu
events would use, if Sensu events used postgresql.

The number of reader/writer goroutines is tunable, as is the total number of
events.
