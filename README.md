## Docker Compose

* ```docker-compose build```
  * realiza o build do arquivo **docker-compose.yml**
* ```docker-compose up -d```
  * cria os volumes, redes e containers definidos nas seções do arquivo **docker-compose.yml**
  * ```-d``` para executar os containers descritos em segundo plano
* ```docker-compose down -v```
  * reverte todo o processo de criação de volumes, redes e containers criados com o ```docker-compose up```
  * ```-v``` para forçar a remoção dos volumes criados

## Nomenclatura

* todos os nomes dos volumes, redes e containers criados com a abordagem **docker-compose.yml** são precedidos do nome do diretório em que ele se encontra
  * **Volume** ```docker-compose-cli-commands-samples_volume-mysql```
  * **Rede** ```docker-compose-cli-commands-samples_backend```
  * **Container** ```docker-compose-cli-commands-samples_mysql_1```
    * o sufixo com a numeração, no caso do container, é definido automaticamente pelo **docker-compose**