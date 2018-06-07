Please change to database connection info on .env and vendor\laravel\lumen-framework\config\database.php because database parameters on my machine are bit different from defaluts.

Please manually create a user in data base, I was unable to add that functionality.

Login
http://localhost:<port>/api/login/?email={Email}&password={password}

Get all items
http://localhost:<port>/api/todo

Create item
http://localhost:{port}/api/todo/?todo={Name}&description={description}&category={category}

Edit item
http://localhost:{port}/api/todo/{id}/?{items to edit}={new values}&..

Delete item
http://localhost:{port}/api/todo/{id}

