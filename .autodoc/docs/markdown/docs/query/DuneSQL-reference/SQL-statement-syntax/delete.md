[View code on GitHub](https://dune.com/docs/query/DuneSQL-reference/SQL-statement-syntax/delete.md)

## DELETE

The `DELETE` section of the app technical guide covers the process of deleting rows from a table in the Dune Docs project. The `DELETE` command is used to remove one or more rows from a table based on a specified condition. The syntax for the `DELETE` command is as follows:

``` text
DELETE FROM table_name [ WHERE condition ]
```

The `WHERE` clause is optional and is used to specify a condition that must be met for the rows to be deleted. If the `WHERE` clause is not specified, all rows from the table will be deleted.

The `Examples` section provides some sample use cases for the `DELETE` command in the Dune Docs project. The first example shows how to delete all line items that were shipped by air. The second example shows how to delete all line items for low priority orders by using a subquery to select the order keys for low priority orders. The third example shows how to delete all orders from the `orders` table.

The `Limitations` section notes that some connectors may have limited or no support for the `DELETE` command. Users are advised to consult the connector documentation for more information.

Overall, the `DELETE` section of the app technical guide provides a clear and concise explanation of how to use the `DELETE` command in the Dune Docs project. The examples provided help to illustrate the different ways in which the `DELETE` command can be used, while the limitations section provides important information about potential issues that users may encounter when using the command.
## Questions: 
 1. What type of database is this `DELETE` command applicable to?
- The app technical guide does not specify the type of database, so the blockchain SQL analyst may need to refer to the connector documentation to determine if it is compatible with their specific database.

2. Are there any restrictions on the use of the `WHERE` clause?
- The app technical guide does not mention any restrictions on the use of the `WHERE` clause, but the blockchain SQL analyst may need to refer to the connector documentation to determine if there are any limitations or differences in syntax.

3. How does this `DELETE` command affect the blockchain data?
- The app technical guide does not mention any specific impact on blockchain data, so the blockchain SQL analyst may need to consider how this command fits into the overall blockchain architecture and data flow.