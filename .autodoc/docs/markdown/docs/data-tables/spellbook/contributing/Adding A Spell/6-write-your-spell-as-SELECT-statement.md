[View code on GitHub](https://dune.com/docs/data-tables/spellbook/contributing/Adding A Spell/6-write-your-spell-as-SELECT-statement.md)

This technical guide covers the process of writing a Spell as a SELECT statement in the Dune Docs project. The guide is focused on the app folder of the project. The guide starts by explaining that the endpoint is `_view_job_log.sql`, but the process should start with `_view_job_migrations.sql` because it is the lowest-level dependency. The guide then explains how to migrate from V1 abstraction to V2 Spell by copying the contents of the V1 file to the `keep3r_network_ethereum_view_job_migrations.sql` file. The guide explains that the `CREATE` or `REPLACE` definition statement is not needed, and everything from the first `SELECT` to the last `TRUE` is required. The guide then explains how to replace hard-coded references with JINJA templating. 

The guide provides examples of SQL code and explains how to modify the syntax to V2/Spark SQL. The guide also explains how to replace hard-coded references with JINJA templating. The guide provides examples of how to format references to sources and models using JINJA. The guide emphasizes the need to test the SQL code in dune.com and fix any errors. The guide also provides tips on how to fix errors by googling or asking for help in the community's Discord channel. 

In summary, this technical guide provides a step-by-step process of writing a Spell as a SELECT statement in the Dune Docs project. The guide covers how to migrate from V1 abstraction to V2 Spell, how to replace hard-coded references with JINJA templating, and how to test the SQL code and fix errors.
## Questions: 
 1. What is the purpose of the dune docs app?
- The app technical guide does not provide information on the purpose of the dune docs app.

2. What programming languages or technologies are used in this app?
- The app technical guide mentions the use of SQL, PostgreSQL, Spark SQL, and JINJA templating.

3. What is the process for migrating from V1 abstraction to V2 Spell style?
- The app technical guide provides a detailed process for migrating from V1 abstraction to V2 Spell style, including modifying syntax to Spark SQL, replacing hard-coded references with JINJA templating, and testing individual SQL files in dune.com.