# MySQL to MS SQL schema creation and data transfer

> **Note:** All the commands are based on a Unix based system such as _OSX_.
> For a different system look for similar commands for it.
> You need an instance of both MySQL and SQL server running.

## Setup

We are using Python version 3.9.7

```bash
$ python --version
Python 3.9.7
```

### Python virtual environment

**Create** a virtual environment:

```bash
$ python3 -m venv .venv
```

`.venv` is the name of the folder that would contain the virtual environment.

**Activate** the virtual environment:

```bash
$ source ./.venv/bin/activate
```

### Requirements

```bash
(.venv) $ pip install -r requirements.txt
```

### .env secrets

1. Create file called `.env` that has a similar input to the format of `sample.env`
   ```
	MYSQL_USERNAME = ""
	MYSQL_PASSWORD = ""
	MYSQL_HOST = ""
	MYSQL_DATABASE = ""
	MYSQL_PORT = ""

	MS_USERNAME = ""
	MS_PASSWORD = ""
	MS_HOST = ""
	MS_PORT = ""
	MS_DATABASE = ""

    ```

2. Fill in the values appropriately

## Run the queries

Open a **jupyterlab** instance

```bash
$ jupyter-lab
```

The code should be present in the `data-transfer.ipynb` file.

■
