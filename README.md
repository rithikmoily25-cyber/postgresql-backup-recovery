# PostgreSQL Backup and Recovery

## Objective
Learn and perform PostgreSQL backup and recovery operations.

## Backup Methods

### Logical Backup
- pg_dump
- pg_dumpall

### Restore Methods
- pg_restore
- psql

## Sample Commands

Backup Database:
pg_dump -U postgres dbname > backup.sql

Restore Database:
psql -U postgres dbname < backup.sql

## Skills Demonstrated

- Backup and Recovery
- Disaster Recovery Basics
- PostgreSQL Administration
- Database Maintenance
