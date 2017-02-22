## convert-db-to-csv

convert-db-to-csv.sh is a shell script that uses SQLite3 to convert a .db file into .csv files. It converts each of the tables in the database into csv files. 

![example](https://media.giphy.com/media/26BGqbh9LLyVjylMc/source.gif)

### Requirements

- [SQLite3](https://www.sqlite.org)
- Bash Shell

### Installation
	
- Clone repository.

	```sh
	$ git clone https://github.com/darrentu/convert-db-to-csv
	```

### Usage

- Enter into directory. 

    ```sh
    $ cd convert-db-to-csv
    ```
	
- Run convert-db-to-csv.sh with the database file as the first argument. 


	```sh
	$ ./convert-db-to-csv.sh example.db
	```

- If the database file is not in the same directory, put in the file path. 

	```sh
	$ ./convert-db-to-csv.sh ~/Library/Safari/History.db
	```

### License

[MIT](./LICENSE) © [Darren Tu](https://github.com/darrentu).