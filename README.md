# DBMS




---------------------------------------------------------------------------------------------------------------------------------------------------------------------1.Difference between Truncate and Delete Command?
   DELETE:
       It is used to delete one or all records in table.
              EXAMPLE: DELETE FROM TABLE_NAME;
                       COMMIT;
                       DELETE FROM TABLE_NAME WHERE NAME="ANU";
                       COMMIT;
       It is can use WHERE condition(ie can filter the table).
       It is DML command so it needs to be COMMIT(to save the changes made).It can ROLLBACK.
       It is slower than TRUNCATE.
  TRUNCATE:
      It is used to truncate all records.
         EXAMPLE:TRUNCATE TABLE TABLE_NAME;
      WHERE condition cant be used.
      It is DDL command so there is no need for COMMIT.
      It is Faster than Delete.
