# COMMONLY USED SQL COMMANDS

## LIST ALL USERS IN MYSQL
```
SELECT User, Host FROM mysql.user;
```
## SHOW CURRENT USER
```
SELECT user();
```
## GRANT ALL PRIVILEGES ON A *SPECIFIC DATABASE* TO A USER
```
GRANT ALL ON database_name.* TO user@localhost;
```

## GRANT ALL PRIVILEGES ON *ALL DATABASES* TO A USER
```
GRANT ALL ON *.* TO user@localhost;
```

## SHOW PRIVILEGES A USER HAS ON A DATABASE(s)
```
SHOW GRANTS FOR user@localhost;
```

## REMOVE ALL PRIVILEGES FROM A USER
```
REVOKE ALL ON database_name.* FROM user@localhost;
```
