# Dotenv

> Load variables from the .env file.

Script to load variables described in a `.env` file before executing given command.

## Usage

Create a `.env` file.

```
PORT=3000
```

Then run your command prefixing it with `./dotenv`. e.g.

```shell
$ ./dotenv rails server
```

You also can _source_ the script to load the variables into a bash script.

```bash
source ./dotenv
echo $PORT
```

## License

The MIT License © 2017 Arthur Corenzan
