## Docker Compose

* ```docker-compose build```
  * realiza o build do arquivo **docker-compose.yml**
* ```docker-compose up -d```
  * cria os volumes, redes e containers definidos nas seções do arquivo **docker-compose.yml**
  * ```-d``` para executar os containers descritos em segundo plano
* ```docker-compose down -v```
  * reverte todo o processo de criação de volumes, redes e containers criados com o ```docker-compose up```
  * ```-v``` para forçar a remoção dos volumes criados