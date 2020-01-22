# Spring Config Server

### Importante
* Servidor de configuração : lugar central para definir as configurações dos serviços
* As configurações dos microsserviços devem ficar externalizadas e centralizadas
* Spring Config Server é uma implementação do servidor do projeto Spring Cloud
* configurar o nome do microsserviço, profile e URL do Config Server
* @EnableConfigServer utilizar para habilitar
* Incluir a dependência config server no Spring Boot  
* As configurações do config-server devem ficar num arquivo application.yml
* As configurações do mciro-serviço (conexão c/ bd, por exemplo) devem ficar no arquivo e na pasta especificada no application.yml do config-server
* [Para requisitar as configurações de um micro-serviço](http://localhost:8888/fornecedor/default) 

