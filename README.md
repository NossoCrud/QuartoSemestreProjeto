Trabalho final da disciplina de Projeto Prático em Sistemas, no curso de graduação em Tecnologia em Análise e Desenvolvimento de Sistemas, Universidade Nove de Julho - Uninove, 4° Período.

Alunos:

Adriana Vilanova dos Santos, RA 2222106311

Anderson Fernandes Filho, RA 2222102272

Gabriella Silva Pascoto, RA 2222101861

Matheus Tenório da Silva, RA 2222101468

Mauro Gabriel Cesar Pereira, RA  2222100490



Trata-se de um CRUD web, feito em PHP, publicado no endereço https://nossocrud.online/ 
O vídeo de apresentação no youtube está no link: https://www.youtube.com/watch?v=tXkRn-O8FKg

O sistema cadastra, lista, permite alterar e excluir registros. São 4 campos solicitados (Nome, e-mail, DDD e Celular), todos de preenchimento obrigatório. Caso algum campo não seja preenchido, o sistema impede que seja dado o comando para cadastrar. São feitas validações para que o e-mail preenchido tenha um formato válido e para que o Celular e o DDD sejam preenchidos obrigatoriamente com números e no tamanho adequado (9 dígitos para celular e 2 dígitos para o DDD). Somente se todos todos os campos estiverem preenchidos da forma correta é que será permitida a gravação no banco de dados.

Depois de cadastrado, o registro aparece em uma lista, e pode ser alterado ou excluído. A opção alterar exibe uma janela em pop-up, com os campos já preenchidos, para melhor experiência do usuário. São feitas as mesmas validações de formato, antes de se salvar o registro. Também é pedida uma confirmação para o usuário, se deseja confirmar a alteração. Se confirmado o registro é alterado no banco de dados.

Caso o usuário clique na opção excluir, antes de apagar o registro, é dada uma mensagem de alerta, avisando que é uma ação irreversível e o registro é apagado somente se o usuário prosseguir com a exclusão. 

As mensagens de interação com o usuário foram feitas em JavaScript e o estilo da página foi feito em CSS e Bootstrap.



