# target-postgres

## Overview
This is a [Singer](https://singer.io) target for Postgres
following the [Singer spec](https://github.com/singer-io/getting-started/blob/master/SPEC.md).
 
## Notes
- This is a fork from the official Meltano Singer PostgreSQL Target. It was forked because this target doesn't work with the combination of Meltano and PostgreSQL that we have. This is because it is using an older version of psycopg2. 
There is already a PR open on the official repository with the fix, but it has been open for several months already. Once it is merged we could stop using this repository. 

