- Teste realizado de acordo com o solicitado.

Para executar o projeto basta seguir os passos:

1 - Acessar a pasta "src" do projeto via command.

2 - Executar docker-compose build

3 - Executar docker-compose up

4 - Executar o comando update-database

(Executei via visual studio alterando a string de conexao para localhost)

Obs: Não criei volume no docker-compose por se tratar de uma aplicação de teste/apresentação,
portanto as informações e execução do update-database valerão apenas em memória, enquanto o container estiver rodando.
