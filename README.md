# NoScope
Plataforma de distribuição de jogos através de moeda virtual, feito em PHP, MySQL e Bootstrap 3 para parte visual, há também algumas funções em AJAX.

## NoScope
=======================
Sistema feito para o Trabalho de Conclusão de Curso para o curso Técnico em Informática do Insituto Federal do Sul de Minas Gerais Campus Inconfidentes.
### DEMO
[http://github.adriel.eu/NoScope](http://github.adriel.eu/NoScope)
#### CREDENCIAIS ADMINSTRADOR
User: admin
Pass: admin

### Instalação:
#### Requerimentos:
- Apache 2, NGINX ou outro servidor HTTP
- PHP 5.4+
- MYSQL 5.6+

#### Instalando o sistema básico
1. Faça o download dos arquivos desse repositório e coloque dentro da pasta **www** do seu servidor  HTTP preferido (apache, nginx ou outro);
2. Altere os dados de conexão do MySQL no arquivo _/classes/mysql.php_
3. Altere as configurações básicas no arquivo _/libs/constants.php_
4. Divirta-se

#### Instalando o chat

1. Abra o arquivo ajax/chat_server.php
2. Edite as linhas 
**_$host = '172.28.1.145'; //Com o IP do servidor que está como host
$port = '9000'; //Com a porta que você quer que o Chat funcione_**
3. Inicie o servidor de Chat com o comando > php -q ajax/chat_server.php


Desenvolvido por Adriel Cardoso dos Santos(Turox)
Professor orientador Ivan Paulino Pereira
