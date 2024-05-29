Attention, le container est mappé au port 1522

docker run -d -p 1522:1521 -e ORACLE_PASSWORD=oracle -e APP_USER=admin -e APP_USER_PASSWORD=password gvenzl/oracle-xe