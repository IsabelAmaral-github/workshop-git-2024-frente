Workshop de Git 2024
======================

por [Bernardo Quaresma](mailto:bernardo@tegraf.puc-rio.br)


O que é?
--------

Git é uma ferramenta para gerenciamento distribuído de versões de um projeto composto por conjunto de arquivos e pastas.

Cada modificação em um ou mais arquivos gera uma nova versão do projeto que possui uma apontamento de diferenças para a versão anterior.

O gerenciamento do projeto é considerado distribuiído porque pode ser feito em ramos e máquinas independentes.

Além de armazenamento e versionamento dos arquivos do projeto, o Git oferece uma forma de incorporar modificações feitas no mesmo arquivo de ramos independentes em um ramo principal.


Porque Git?
-----------

A possibilidade de desenvolver e testar novas funcionalidades e melhorias de forma distribuíde e independente facilita a divisão e planejamento do trabalho.

Além disso, infraestruturas como GitHub e GitLab oferecem ferramentas de criação e atribuição de pendências (issues) que dinamizam o gerenciamento de projetos com equipes distribuídas.

Finalmente, com o Git é possível desenhar um fluxo de trabalho comum que reduz a necessidade de comunicação instantânea entre os integrantes do projeto.


Como Usar?
----------

  - Repositórios Remotos x Locais
  - Acessando o repositório de um projeto remoto (GitHub)
  - Criando um Repositório local (Clone)
  - Ramificando o desenvolvimento (Branch)
  - Modificando o ramo local (Stage/Commit)
  - Atualizando o repositório remoto (Push)
  - Integrando os Ramos de Desenvolvimento (Pull/Merge Request)


Exercício
---------

1. Repliquem este projeto (Fork) no GitHub
2. Dividam os tópicos da próxima seção entre vocês
3. Clonem o projeto replicado na máquina de vocês
4. Criem ramos locais nomeando com um breve descrição da pendência que estão resolvendo (Ex: Formatacao)
5. Preencham o tópico atribuído para você (vale consulta)
6. Modifiquem o ramo local com as alterações incluindo uma mensagem que a descreva
7. Atualize o repositório remoto com o ramo criado


Markdown
--------

Markdown é uma forma de escrever arquivos texto seguindo regras que serão seguidas para exibição do texto com formatação.

### Formatação

#### Itálico
Para formatar um texto em itálico utilize o * no inicio e fim do texto.
  *texto em itálico*

#### Negrito
Para formatar em negrito utilize ** no inicio e no final
  **Negrito**

#### Bloco de Código
Para criar um bloco de código de várias linhas específico, adicione três acentos graves (```) antes e depois do bloco de código.
Exemplos:
Oi ```sou diferente```de vocês. 

### Listas

#### Listas Numeradas
Para fazer listas númeradas é necessário usar os númerospara cada elemento da lista.

Por Exemplo:
1. Primeiro item
2. Segundo item
3. Terceiro item


#### Listas com subitems

para formatar uma lista com subitens colocar um * na frente do item e dar um tab nos subitens para cada item
(segundo o tutorial do google de markdown pq eu n sei fazer isso n).
Aqui está um exemplo: 

* frutas:
  * banana
  * maça
  * uva
* Carnes:
  * frango
  * boi
  * porco  


#### Listas de Tarefas
 para fazer uma lista de tarefas colocar um - na frente e depois um [ ] e em seguida a tarefa, quando a tarefa estiver completa colocar um x entre os colchetes, assim: "[x]"
Aqui vai um exemplo:
- [ ] Tarefa incompleta
- [x] Tarefa completa


### Tabelas
Para criar uma tabela, utilize '|' e '-'. Para delimitar o cabeçalho de cada coluna, utilize os '-' e, para delimitar as colunas, utilize os '|'.

Exemplo:

|Cabeçalho 1|Cabeçalho 2|
|-----------|-----------|
|Item 1.1|Item 1.2|
|Item 2.1|Item 2.2|


Anotações
---------

Usem esse espaço para manter uma lista de anotações e dicas como comandos do Git, links do GitHub e exemplos de Markdown.

Malu
1. Sempre lembrar de mudar para onde fazer o *"pull request"* para evitar problemas!
2. É possível associar um *merge pull request* para outra pessoa, só clicando em um botão lateral!
3. Também clicar em *staged changes* no VSCode quando for commitar!
4. Também é necessário se lembrar de dar **sync** e **pull** no VSCode após você ter feito mudanças (*merges*) na main através do site do GitHub!



3. Nao tava certo la a lista com sublista e depois eu tive que consertar entao e bom pelo aprendizado para aprnder a fazer branches novas para revisao do codigo 