# Tutoriais dos quadros do Jira

### Encontrar e criar um quadro do Jira

Navegue até “Quadro” na barra lateral à esquerda. Para criar um quadro adicional, abra o menu suspenso e clique em + **Criar quadro**.

![Captura de tela de um quadro do Jira](https://wac-cdn.atlassian.com/dam/jcr:021c34e9-4358-446b-bbe5-7eef30f014a1/UIF-Kanban-Navigate.png?cdnVersion=2537)

**Observação:** no momento não é possível criar quadros adicionais em um projeto gerenciado pela equipe.

### Configurar colunas em quadros do Jira

**Em projetos gerenciados pela equipe:**

1. Acesse o quadro. Clique em **(•••)** no canto superior direito e depois em **Configurar quadro**.
2. Adicione uma nova coluna, altere o nome da coluna, exclua uma coluna, mova uma coluna ou agrupe vários status em uma coluna, conforme necessário. [Saiba mais](https://support.atlassian.com/jira-software-cloud/docs/manage-columns-with-multiple-statuses-in-a-team-managed-project/)

**Em projetos gerenciados pela empresa:**

1. Acesse o quadro. Clique em **(•••)** no canto superior direito e depois em **Configurações do quadro**.
2. Clique na guia **Colunas**.
3. Adicione uma nova coluna, altere o nome da coluna, exclua uma coluna, mova uma coluna ou agrupe vários status em uma coluna, conforme necessário. [Saiba mais](https://support.atlassian.com/jira-software-cloud/docs/configure-columns/)

### Visualizar raias no quadro do Jira

**Em projetos gerenciados pela equipe:**

Navegue até o quadro. No canto superior direito, abra o menu suspenso **Agrupar por** e escolha como visualizar as raias: por responsáveis, epics ou subtarefas.

**Em projetos gerenciados pela empresa:**

1. Navegue até o quadro. Clique em **(•••)** no canto superior direito e depois em **Configurações do quadro**.
2. Clique na guia **Raias**.
3. Configure as raias por histórias, consultas, responsáveis, epics ou projetos. [Saiba mais](https://support.atlassian.com/jira-software-cloud/docs/configure-swimlanes/)

### Criar filtros personalizados para o quadro do Jira

Os filtros rápidos personalizados facilitam a localização e o acesso aos itens nos quais você trabalha com frequência.

**Em projetos gerenciados pela equipe:**

1. Navegue até **Configurações do projeto** > **Quadro** > **Filtros personalizados** na barra lateral.
2. Insira um nome e uma descrição para o filtro personalizado.
3. Escreva uma consulta de filtro [usando JQL](https://www.atlassian.com/br/software/jira/guides/jql/overview). Conforme você digita, o Jira valida a consulta e oferece uma lista de sugestões de preenchimento automático com base no contexto da consulta. Clique em **Criar**.
4. Depois de criar o primeiro filtro personalizado, um novo menu suspenso é exibido na visualização do quadro. Clique em filtros para refinar a pesquisa e use vários filtros ao mesmo tempo para restringir os itens de que você precisa.
5. Você pode editar e excluir filtros personalizados a qualquer momento. Clique em (•••) no quadro ou backlog e, em seguida, em **Gerenciar filtros personalizados**.

[Saiba mais](https://support.atlassian.com/jira-software-cloud/docs/manage-custom-filters-in-team-managed-projects/)

**Em projetos gerenciados pela empresa:**

1. Navegue até o quadro. Clique em **(•••)** no canto superior direito e depois em **Configurações do quadro**.
2. Clique na guia **Filtros rápidos**.
3. Escreva uma consulta de filtro [usando JQL](https://www.atlassian.com/br/software/jira/guides/jql/overview).
4. Os filtros são exibidos acima do quadro.

### Criar um quadro entre projetos por meio de filtros personalizados

1. Crie um [filtro personalizado](https://www.atlassian.com/br/software/jira/guides/jql/tutorials#advanced-search) usando JQL na navegação superior **Filtros > Pesquisa avançada de itens**.
2. Crie um quadro em um projeto gerenciado pela empresa.
   1. Navegue até **Quadro** na barra lateral à esquerda. Clique no menu suspenso e selecione **+ Criar quadro**.
   2. Selecione Scrum ou Kanban.
3. Aplique o filtro ao quadro.
   1. Clique em **Quadro a partir de um filtro salvo existente**.
   2. Dê um nome ao novo quadro.
   3. Procure o filtro.
   4. Clique em **Criar quadro**.
4. No novo quadro, você pode aplicar status de mapeado ou não mapeado às colunas do quadro sem afetar [outros quadros](https://www.atlassian.com/br/software/jira/guides/boards/tutorials#configure-columns).