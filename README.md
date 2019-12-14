# Objetivo

O objetivo do sistema é facilitar o trabalho da funcionária quando for necessário atualizar os cartórios.

Para impedir o excesso de trabalho repetitivo, basta clicar no botão "Checar xml" e inserir o link xml do cliente no campo
e processar a varredura.

O sistema vai varrer os dados do xml e salvar todos os valores necessários no banco de dados.

Logo em seguida, vai listar todos os dados salvos.

A partir desse momento já será possível atualizar e excluir todos os dados.

Também sera possível cadastrar um novo dado se necessário for.

O Sistema também disponibiliza de um campo para filtrar dados.

# Tecnologias usadas

Para este desafio, usei apenas:

- PHP orientado à objetos
- Um micro-framework extensivel para PHP chamado Flight, documentação: http://flightphp.com/
   - Usei para facilitar o roteamento.
   
- Composer para gerenciar as dependências.
- Bootstrap e Jquery
- sweetAlert, documentação: https://sweetalert.js.org/guides/
- Mysql
- Apache server

# Estrutura
- Construí a aplicação baseado em MVC
