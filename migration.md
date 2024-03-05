# migration commands

pg_dumpall -U username_user-database > filename.sql

# for stop process in database

SELECT pg_terminate_backend(pid) FROM pg_stat_activity WHERE datname = 'name_database';

