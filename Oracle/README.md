## Drop an existing table space
`drop tablespace <TABLE_SPACE_NAME> including contents and datafiles;`

## Create a new table space
`create tablespace <TABLE_SPACE_NAME> datafile '<TABLE_SPACE_NAME>.dbf' size 250M autoextend on maxsize unlimited;`

## Create a new tablespace with smaller size
`create tablespace <TABLE_SPACE_NAME> datafile '<TABLE_SPACE_NAME>.dbf' size 250M autoextend on next 256m maxsize unlimited;`
