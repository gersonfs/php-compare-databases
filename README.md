PHP compare databases
=====================

A Codeigniter Controller to determine if 2 mySQL Databases such as a 'Development' and a 'Live' database have the same tables and table structures.

It can determine in a very basic way if there are tables of the same name on the Development and Live database that have differences in their structure and need to be updated.

It will show the SQL commands needed to create/drop tables in the Live database if required.

It will show the SQL commands needed to create/modify/drop fields in the Live database if required.

It does not make any changes to the Live database, instead it lists the SQL commands so a user can decide to run them or not.