# Teste para novos devs - To Do List
Olá dev! Ficamos muito felizes pelo seu interesse em fazer parte do nosso time!

Este teste serve para que possamos entender melhor seu momento profissional e experiência com tecnologia para que nossa negociação possa ser a mais justa possível tanto para a empresa quanto para você.

## O teste :fearful:
O teste consiste no desenvolvimento de uma To Do List básica. Procuramos incluir o menor número de requisitos possíveis que nos permitam avaliar seus conhecimentos.

### O que será avaliado? :heavy_check_mark:
1. Qualidade e clareza do código;
2. Organização;
3. Cuidado com o funcionamento das coisas;
4. Versionamento.

**Obs:** Não será avaliado o design das telas entregues, porém sugerimos utilizar como referência os boards da plataforma Trello.

### O que deve ser desenvolvido? 👨‍💻
Como já mencionado, o sistema a ser desenvolvido neste teste é uma To Do List. Nela deve ser possível cadastrar as colunas do seu To Do, como por exemplo a fazer, fazendo, feito e etc. As colunas devem ser cadastradas informando nome da coluna e sua a prioridade.
A prioridade das colunas deve ser utilizada para definir a ordem de exibição das mesmas. Ou seja, uma coluna com prioridade 1, deve ser exibida antes de uma coluna cadastrada com prioridade 2 e assim por diante.

Após cadastrar as colunas, deve ser possível cadastrar e remover tarefas na sua To Do List. Além disso, deve ser possível alterar o status das tarefas.
O status de uma tarefa é a coluna em que ela se encontra no To Do. Sempre que uma tarefa for cadastrada, ela deve ser vinculada/exibida na coluna de menor prioridade.
**Importante:** Não é necessário trabalhar com drag and drop para mover as tarefas entre as colunas, mas sempre que o status de uma tarefa for alterado ela deve ser exibida na coluna correta.

Além disso, deve ser possível excluir os status/colunas do seu To Do List, mas tome cuidado para não permitir exclusão de status que possuem tarefas.

**Para facilitar sua avaliação de que seu To Do List cumpre com todos os requisitos, listamos tudo aqui em tópicos. Seu To Do List deve:**
1. Cadastrar e remover status/colunas com seu nome e prioridade (numérico);
2. Cadastrar tarefas e permitir alterar seu status;
3. Remover tarefas cadastradas;
4. Quando as tarefas quando tem seu status alterado devem ser movidas para a coluna correta;
5. Não deve ser possível remover um status que possua tarefas.

## Requisitos técnicos :electric_plug:
São requisitos obrigatórios para execução do teste:

1. Backend deve ser feito em PHP 7.0+ ou NodeJS, podendo ser utilizados frameworks a critério do desenvolvedor;
2. Deve ser utilizado banco de dados relacional para armazenamento das informações. Recomendamos MariaDB ou MySQL;
3. O front-end deve ser desenvolvido utilizando HTML, CSS e JS. Caso queira, o desenvolvedor pode utilizar frameworks JS, webpack, SASS e tecnologias do tipo. **NÃO utilizar JQuery**, uma vez que está é uma tecnologia fora da stack da Insus.

Não é um requisito obrigatório mas será considerado um plus a utilização de docker e docker-compose.

## Como entrego meu teste? :package:
1. Faça um fork deste repositório para sua conta no GitHub, deixando o teste como privado;
2. Desenvolva o teste utilizando a organização de branches com a qual estiver mais confortável;
3. Dê acesso ao seu repositório para as contas RaphaelBatagini e felipefanucchi.

Envie um e-mail para raphaelbatagini@insus.com.br e felipefanucchi@insus.com.br com o assunto "Teste Insus" informando a conclusão do teste e com um link para seu repositório.

Desejamos sorte no seu teste e que possamos trabalhar juntos em breve!
