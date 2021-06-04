# desafio-seazone

Foram criados 3 apps: Reservas, Anúncios e Imóveis, cada app produziu uma tabela no banco de dados, os modelos responsáveis pela geração das tabelas se encontram no arquivo "models.py" de cada app.

Para cada app foram criados 4 arquivos ".html", sendo um para adição de informações,  um para edição, um para exibição em lista e outro para exibição individual. Para cada arquivo foi criada uma url que pode ser conferida no arquivo "url.py" de cada app.

Devido ao tempo demandado para o estudo das novas ferramentas (Django e Django REST Framework) e habituação das funções, o sistema se encontra inacabado, sendo que as principais deficiencias se encontram na falta de checkagem de alguns dados de entrada, bem como na falta da exibição de mensagens de erro para usuário no front-end.

Para executar, basta abrir um terminal no diretório "Desafio Seazon/projeto/desafio/", executar o comando "python .\manage.py runserver" e acessar a "local-host". Caso queira obter privilégios de administrador, basta acessar "local-host/admin" entrar com usuário: admin e senha: admin.
