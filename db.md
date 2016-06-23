Database Tables
===============

Types:
 * ID: string, hex, 32chars

All tables:
 * Version: int
 * changed_at: int (timestamp)
 * deleted: bool

Accounts
--------

 * ID
 * Name
 * Type
 * Comment
 * Closed

Transaction
-----------

 * ID
 * Account
 * Other (Account or other entity)
 * Budget
 * Comment

CategoryGroup
-------------

 * ID
 * Name

Category
--------

 * ID
 * Name
 * Group
 * Type
 * Amount
 * Due

Budget
------

 * ID
 * Month
 * Category
 * Amount
 * Overspending
