# Desafio Digitaliza - Teste Técnico

Olá, você quer ser desenvolvedor na Digitaliza?
Então criamos este teste para avaliar alguns pontos tecnicos como desenvolvedor BackEnd!

## Teste 
O desafio é desenvolver um sistema para câmaras de cadastro, e exibição de projetos de lei ao público.
O sistema terá 3 lados,sendo um lado master, outro do vereador e um público.

O Projeto não precisa ser focado com o front end, não precisa se atentar a detalhes estéticos nesta parte, podendo até usar algum template pronto gratuito da internet.

### Lado Master
O Usuário master terá a possibilidade de cadastrar novos vereadores e comissões.
- Os vereadores terão dados de login e suas informações pessoais.
- As comissões terão
  - Dados sobre a comissão: como nome da comissão e partido.
  - E as comissões terão vereadores vinculados a mesma, onde uma comissão poderá ter varios vereadores e um vereador poderá fazer parte de várias comissões.

### Lado Vereador

O vereador terá a disposição de um login, onde ele poderá ser autenticado e fazer os cadastros de seus projetos de lei.

Um projeto de lei possui os seguintes dados:

- Número do Projeto de Lei
- Ano do Projeto de Lei
- Data do Projeto de Lei
- Autoria (Tendo a possibilidade de escolher um dos itens)
  - Poder Executivo
  - Poder Legislativo
  - Iniciativa Popular
  - Câmara
- Tipo (Tendo a possibilidade de escolher um dos itens)
  - Decisão 
  - Decreto
  - Lei
  - Proposição de Lei
  - Emenda
  - Veto
- Ementa
- Comissão (Onde ele terá possibilidade escolher algumas das comissões cadastradas)
- Arquivo do Documento do Projeto de Lei

### Lado Público
Esta parte será onde os cidadãos poderão ver todas as leis cadastradas como forma de transparência.
Onde será necessário listar todas as leis, e detalhar suas informações, e comissões vinculadas.

## Requisitos 

 - Ser desenvolvido utilizando PHP 8+
 - Ser desenvolvido utilizando o framework Laravel em sua versão 9
 - Banco de dados Mysql/Maria DB
 - Ter um código limpo e organizado utilzando as normas de Clean Code.
 - Utilizar boas práticas de desenvolvimento.
 - Fazer validações de formulãrio.
 
## Diferenciais
- Ao vincular um vereador a uma comissão notifica-lo por email.
- Notificar a todos os vereadores por email que um novo projeto de lei foi cadastrado.
- Criar uma documentação para o projeto.



  