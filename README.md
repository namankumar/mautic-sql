# Mautic SQL notes

Queries I collected while working with Mautic campaign events, segments, and email records. The examples are in [mautic_sql_queries.txt](mautic_sql_queries.txt).

They cover event counts, overlapping segment membership, anonymous contacts, and email-copy records. They are working notes, not migrations or a script to run from top to bottom.

## Before using a query

Read it against your Mautic version and schema. Replace the example IDs, preview the affected rows with `SELECT`, and work on a backup or disposable copy first. Some examples use `DELETE` and `DROP`; they can remove data. Some comments and incomplete fragments are not valid SQL.

No query was executed or validated against a current Mautic database in this documentation pass.
