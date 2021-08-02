

###  docker-compose.yml
```shell
db:
    image: postgres
    ports:
        - "5432:5432"
    environment:
        POSTGRES_USER: "user_pg"
        POSTGRES_PASSWORD: "user_pg"
```


### Requirements
```shell
pip install beautifulsoup4
pip install lxml
pip install psycopg2-binary
pip install requests

pip install tabula-py
pip install selenium
pip install PyVirtualDisplay
```