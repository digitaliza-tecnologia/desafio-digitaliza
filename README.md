# Desafio Digitaliza - Teste Técnico

Olá, você quer ser desenvolvedor na Digitaliza?
Então criamos este teste para avaliar alguns pontos tecnicos como desenvolvedor BackEnd!
Você terá um teste para resolver, e dois formulários teóricos a ser respondidos!

## Formulários Teóricos:
- Teste de Mysql/MariaDB: https://docs.google.com/forms/d/e/1FAIpQLSdv25HG_75YuUzTk_5J3PDqXd08BP_NQy1Yw3S9TYxh7_yG4Q/viewform?usp=sf_link
- Teste de Shell Linux (Debian, Ubuntu): https://docs.google.com/forms/d/e/1FAIpQLSeCY6PakOvY_JCjJs6uTwQ_nEEozoMilxODf_jcI22V1Qvtgw/viewform?usp=sf_link

## Teste Prático
O desafio é desenvolver um sistema para câmaras de cadastro, e exibição de projetos de lei ao público.
O sistema terá 2 lados,sendo um vereador e um público.

O Projeto não precisa ser focado com o front end, não precisa se atentar a detalhes estéticos nesta parte, podendo até usar algum template pronto gratuito da internet.

Não é necessário desenvolver um cadastro de comissões e usuários, para isso pode ser criado uma seed para popular as tabelas de usuários e comissões

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



  
