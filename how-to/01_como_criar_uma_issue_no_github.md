# Como criar uma issue no github

## Glossário

[Link para o glossário - issue](https://github.com/mentoriaiac/glossario/blob/main/README.md#issue)

## Objetivo

Esse documento demonstrará os passos necessários para criação de uma issue em um repositório do projeto com base em uma demanda existente.

A demana pode ser técnica, uma falha de segurança, organização ou até mesmo documentação. A demanda é o ponto de partida para uma issue. Não há sentido uma issue sem uma demanda.

## Como começar

Usaremos o exemplo abaixo:

Uma pessoa percebeu que o o ci/cd demorava muito na etapa de build e percebeu que não havia cache de imagens docker no momento de builds dentro do mesmo pipeline. Essa pessoa não necessariamente sabia como resolver o problema e isso não era importante. Ela percebeu a falha e tem o que é suficiente para reportar a issue.

## Reportando a issue

Abra o github no [link do projeto](https://github.com/mentoriaiac) e pesquise no campo "Find a repository" (Talvez esteja em português "Procure seu repositório") o repositório que deseja abrir a issue.

No menu superior, escolha a opção "issues".

Clique no botão "New issues".

Clique no link "Open a blank issue".

No **título** coloque uma descrição clara do problema. Evite informações vagas, que não ofereçam pista alguma sobre o que se trata o tema.

Exemplos de péssimos títulos: 

 - Problema muito grave no ci/cd
 - Erro super estranho no systemd

Exemplos de bons títulos:

 - O ci/cd não tem cache no build da imagem docker
 - Erro "file not found" na utilização do systemd

No campo de descrição coloque os detalhes da issue. Coloque todas informações que você tem, de forma bem ordenada. Para que uma pessoa que nunca passou por esse problema possa entender seu problema.

Segue abaixo um bom modelo do que deve ir na issue:

```
## Descrevendo o problema

Aqui você coloca todos os detalhes do que está acontecendo. Falando sobre o erro em seu detalhe mais profundo que conseguir.

## Reproduzindo o problema

Se fizer sentido, aqui você coloca o passo a passo de como a pessoa passar pelo mesmo problema que você está descrevendo

## DoD

No DoD você coloca uma lista de entregáveis, que você imagina que o ticket não pode deixar de fazer antes de ser fechado.

 - [ ] lista de atividades
 - [ ] lista de atividades 
```

**Obs**: No momento da criação do ticket é muito difícil fazer o DoD, ainda mais se você não tiver experiência do que precisa realmente ser feito pra corrigir. O DoD pode ser feito depois em conjunto com outras pessoas.

Ao terminar de preencher a descrição, você pode clicar no botão "Submit new issue" e pronto. Sua issue estará pronta. Confira se sua issue aparece no [board de observabilidade ou outro projeto que esteja relacioado](https://github.com/orgs/mentoriaiac/projects).
