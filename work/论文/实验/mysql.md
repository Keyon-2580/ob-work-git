docker run --name mysql -v /Users/keyonxie/Documents/docker/mysql/conf:/etc/mysql -v /Users/keyonxie/Documents/docker/mysql/data:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=root -d -p 3306:3306 1402b5eee239d06c8f1a01c16cd0b773e85e808e5c9185a6b36e9b232e776275 --defaults-file=/etc/mysql/my.cnf


