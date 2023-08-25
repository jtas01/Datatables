# Datatables Editor

### Basic examples setup of Datatables with inline editor in PHP & MySQL

### Create a new database and run the SQL from SQL.txt to create the tables used in the examples
### Add database config inside lib/config.php

````PHP
$sql_details = array(
	"type" => "Mysql",    // Database type: "Mysql", "Postgres", "Sqlserver", "Sqlite" or "Oracle"
	"user" => "root",    // User name
	"pass" => "",    // Password
	"host" => "localhost",    // Database server
	"port" => "",    // Database port (can be left empty for default)
	"db"   => "testDB",    // Database name
	"dsn"  => "",    // PHP DSN extra information. Set as `charset=utf8mb4` if you are using MySQL
	"pdo"  => null   // Existing PDO connection. Use with `type` and no other parameters.
)
````

### Run examples from http://localhost/<project_name>/examples/