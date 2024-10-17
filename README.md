# formPage

1- Nas duasprimeiras linhas, acesso o documento HTML, acesso os elementos especificos pelo ID
2- Guardo na variabel tabela as informações relacionadas a tabela de cadastros e a tag tbody na primeira posição ( a primeira tbody )
3- crio um array vazio na constante cadastros.
4- adiciono um Listener no formulario, que basicamente "ouve" as informações, e com isso consegue manipular elas, manipula o evento que está acontecendo no formulario (e), esse listener serve para o botão de submit, e o comando e.preventDefault() impede a pagina de recarregar assim que o formulario for enviado
5- guardo na variavel nome e email as respectivas informmações obtidas usando .value e acessando pelo id
6- Adição do campo de nome e email no array de cadastros, usando o metodo PUSH, adiciono as informações dos respectivos campos.
7 - chamo a função atualizarTabela, mostrando o cadastro atualizado
7.1- e form.reset() para limpar os campos do formulario.
8- criação da função pra atualizar a tabela
8.1 - manipulo a variavel tabela com o metodo .innerHTML pra que ao submit, as informações do campo fiquem vazias
8.2 - faço uma iteração sobre o array de cadastros em que para cada cadastro, eu crio uma nova linha ( row )
8.3 - insiro duas celulas na linha, sendo uma para cada campo
