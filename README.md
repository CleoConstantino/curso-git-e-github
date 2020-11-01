
# Git e Github 
  
O Git é um sistema de controle de cersão (VCS). Não permite o envio de uma alteração antes baixar as alterações que já foram enviadas, para que só então consiga enviar a versão atualizada.

1º passo: instalar o Git Bash;

Comandos:

 - git init: para iniciar um repositório;
 - git status: mostra informações detalhadas;
 - git add .  : passa a monitorar todos os arquivos da pasta atual;
 - git commit -m "mensagem"
 - clear: limpa a tela;
 - git log: mostrará diversas informações sobre o commit;
 - git log-p: mostra alterações realizadas;
 
 Antes de qualquer comando, deve-se informar quem é que está fazendo alterações no código: 
 git config --local user.name "Cléo Constantino"
 git config --local user.email "cleoconstantino@outlook.com"
 
-   `HEAD`: Estado atual do nosso código, ou seja, onde o Git nos colocou
-   `Working tree`: Local onde os arquivos realmente estão sendo armazenados e editados
-   `index`: Local onde o Git armazena o que será  _commitado_, ou seja, o local entre a  _working tree_  e o repositório Git em si.

Para saber mais sobre os status, acessar o link: <[https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Gravando-Altera%C3%A7%C3%B5es-em-Seu-Reposit%C3%B3rio](https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Gravando-Altera%C3%A7%C3%B5es-em-Seu-Reposit%C3%B3rio).

Formatos que podem ser usados para mostrar o histórico: https://devhints.io/git-log
