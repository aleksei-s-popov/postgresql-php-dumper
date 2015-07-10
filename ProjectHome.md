### Description ###
PostgreSQL backup (dump
) tool for tables.
Support versions - 8.3 and later.

### Features ###
  * creating completely dump of a table with full information (sequences, indexes, constraints etc.) **without** using pg\_dump
  * creating sql dump or creating dump in inner dumper format
  * 4 work mode: dump, dump and restore from backup, restore from backup only, delete existing table and restore from backup
  * safe mode support (copying\renaming table instead deleting before restore from dump)
  * multilingual support (us english and russian)

### Requirements ###
  * PHP 5.3 or above with pgsql extension