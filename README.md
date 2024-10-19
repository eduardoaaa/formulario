# formulario

acesso o id do formulario pelo getElementById, e com o .onsubmit = function(evento) eu mostro o que vai ser exibido quando o formulario for enviado no futuro.
o evento.preventDefault() faz com que o formulario não recarregue a pagina quando der submit

acesso o valor do campo de nome e email usando o .value e acessando pelo id, e guardo essas informações nas respectivas variaveis.

atribuo a variavel tabela o tbody ( acessando pelo id ) ficando mais facil de manipular a DOM

na variavel novaLinha crio uma nova linha usando o comando insertRow();

na variavel colunaNome e colunaEmail, uso a variavel novaLinha para que consigua atribuir uma nova linha, e com essa linha insiro uma celula ( um campo no novo campo a ser mostrado ) na posição 0 ( primeira ) para nome e 1 ( segunda ) para email

modifico o valor do colunaNome usando o .innerHTML, para que ele receba as informações guardadas do submit do form, na variavel nome e o mesmo para email.

e com o .reset() eu limpo os campos do formulario já escritos.
