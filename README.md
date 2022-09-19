# Python-db

Python-db is an example of usage of mariadb and postgres from python connector

## Installation

Docker and docker-compose is needed!
After that, run


```bash
docker-compose up -d
docker ps # (check the new container's hash)
docker exec -it <hash> bash
```

## Usage

Once inside the container, run 

```bash

src/db_test.py

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)