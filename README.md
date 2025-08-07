### Basic layout

```
CREATE OR REPLACE PROCEDURE IDE_NAME
AS
BEGIN

END;
```


Hello World
```
CREATE OR REPLACE PROCEDURE IDE_NAME
IS
BEGIN 
DBMS_OUTPUT.PUT_LINE('HELLO WORLD');
END;
/
```

```Output
Procedure created.
```

- After see the above command we have to write the below command and after write below command, we have to select the below three line and run it.
```
BEGIN 
IDE_NAME;
END;
```

```Output
HELLO WORLD

Statement processed.
```


## SQL Command Type
#### DDL - Data Definition Language
**Command**
- create
- alter
- drop
- truncate
- rename
- comment

#### DML- Data Manipulation Language
**Command**
- Update
- Delete
- Select
- Insert

#### DCL - Data Control Language
**Command**
- Grant
- Revoke

## How to create the table

**CREATE Command**
```
CREATE TABLE STU(
	ID NUMBER,
	NAME VARCHAR2(50),
	AGE NUMBER
)
```

**ALTER Command**
- To add any `column` on the table
```
ALTER TABLE STU ADD EMAIL VARCHR2(100);
```

**Select Command**
- Using this command we can see the all the table data
```
SELECT * FROM <Table_Name>
```