# PostgreSQL functions

A repository of custom PostgreSQL functions and extensions.

## global_search
A plpgsql function that finds occurrences of a string in all
or some of the tables of an entire database.  
It returns the table, column and `ctid` of the rows containing
the value.  
The search can be limited to an array of tables and/or of
schemas. Progress is optionally reported by emitting `raise info` messages.

## hamming_weight
C functions that return the number of bits set to `1` in a bytea, int or bigint value.

