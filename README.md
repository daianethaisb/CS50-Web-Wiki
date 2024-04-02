## Project 1 - Wiki:

>  Desenvolvimento e implementação de funcionalidades de enciclopédia online semelhante à Wikipedia em um código de distribuição fornecido pelo curso.

Das funcionalidades implementadas

* Página de entrada: a visita /wiki/TITLE, onde TITLEé o título de uma entrada da enciclopédia, deve renderizar uma página que exibe o conteúdo dessa entrada da enciclopédia;
* Página de índice:  atualização index.htmlde forma que, em vez de apenas listar os nomes de todas as páginas da enciclopédia, o usuário possa clicar em qualquer nome de entrada para ser levado diretamente para essa página de entrada;
* Pesquisa: permite que o usuário digite uma consulta na caixa de pesquisa na barra lateral para pesquisar uma entrada da enciclopédia;
* Nova página: permite a criação de uma nova página na enciclopédia;
* Editar página : em cada página de entrada, o usuário deve ser capaz de clicar em um link para ser levado a uma página onde o usuário pode editar o conteúdo Markdown dessa entrada em um arquivo textarea;
* Página aleatória : clicar em “Página aleatória” na barra lateral deve levar o usuário a uma entrada aleatória da enciclopédia;
* Conversão de Markdown para HTML : Na página de cada entrada, qualquer conteúdo Markdown no arquivo de entrada deve ser convertido para HTML antes de ser exibido ao usuário.

**Como executar o aplicativo**

- Execute as migrações com o comando python manage.py makemigrations.
- Aplique migrações com o comando python [manage.py](http://manage.py/) migrate.
- Execute o servidor usando python [manage.py](http://manage.py/) runserver.
