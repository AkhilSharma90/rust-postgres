1. Check if postgres is installed -> `psql -V`
2. Run postgres server -> `sudo service postgresql start`
3. Open the terminal and use the right user -> `sudo -i -u akhil`
4. Open psql -> `psql`
5. CREATE DATABASE library;
6. Check if the db got created -> `\l`
7. Go inside the db -> '\c library'
8. After running the rust program, check if the tables were created inside the library db -> `\dt`

NOTE -> DB_URL in main.rs file to be replaced by something like this -> postgres://akhil:newpass@localhost:5432/library
