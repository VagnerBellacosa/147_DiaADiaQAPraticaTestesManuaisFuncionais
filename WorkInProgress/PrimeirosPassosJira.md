# Guia de inicialização rápida

### Introdução

Este guia é para quem está começando a configurar um projeto de serviço no Jira Service Management. Se você ainda não tiver feito, [faça a inscrição no Jira Service Management de graça](https://www.atlassian.com/br/software/jira/service-management/free). Quando estiver no Jira Service Management, você pode configurar tudo seguindo as instruções. Caso precise de mais ajuda ou apenas queira ver tudo em um lugar antes de conferir mais informações, este guia é para você.

Observe que este guia é específico para [administradores de projetos](https://support.atlassian.com/jira-service-management-cloud/docs/what-are-user-types-and-roles/) do Jira Service Management. Se você for agente do Jira Service Management, confira o [Guia de integração do agente](https://www.atlassian.com/br/software/jira/service-management/product-guide/tips-and-tricks/agent-onboarding).

### Etapa 1 - Configure e personalize o projeto

#### Crie o projeto de serviço

Jira Service Management has a variety of project templates to help teams get set up quickly by creating projects tailored to a specific team or use. These templates include pre-configured request types, workflows, and other relevant features. There are templates available for IT and customer service management, as well as a range for templates for business teams like HR, finance, and marketing.

![Tela de templates de projeto do Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:cf75fe61-4731-4b8a-aac7-768f4ae7993b/create-your-service-project.png?cdnVersion=2537)

[Saiba mais sobre templates de projeto no Jira Service Management](https://support.atlassian.com/jira-service-management-cloud/docs/what-are-the-project-templates/)

**Para criar um projeto de serviço:**

1. From the top menu bar select **Projects**, then **Create project**.
2. From the **Service management** category, browse the available templates and select the one that best suits your needs.
3. Review the template’s details, and if you’re happy with the one you’ve chosen, select **Use template** (or if you’ve chosen a Blank template, select **Create blank project**).
4. Selecione um tipo de projeto [**gerenciado pela equipe** ou **pela empresa**](https://support.atlassian.com/jira-service-management-cloud/docs/learn-the-differences-between-classic-and-next-gen-projects/). (Observação: os tipos de projeto gerenciados pela equipe só estão disponíveis para determinados templates de projeto.)
5. Dê um nome ao seu projeto.
6. Crie a chave do projeto ou use a chave gerada.
7. Select the type of team that will use the project. This can be changed later in project settings.
8. Select your the channel access to determine who can send requests to this project.
9. If you would like to share settings from an existing project, specify the name of the project.
10. Review your project type selection (If the project template is available in both project types.
11. If you’ve selected a team-managed project type, review the **Access** and **Default language** settings.
12. Selecione **Criar projeto.**

#### Personalize a central de ajuda e o portal

Os clientes acessam a central de ajuda e o(s) portal(is) para solicitar ajuda. A personalização é importante para garantir que você forneça uma experiência de marca consistente na qual os clientes vejam todas as informações relevantes.

![Central de ajuda do Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:6b7055fe-d051-481a-b7fa-80a30b7eaa4d/service-center-updated.png?cdnVersion=2537)

**Personalize a central de ajuda**

Let’s start with the help center. Every Jira Service Management site comes with an online help center. And every service project comes with a portal. From the help center, customers can browse all the service project portals they have access to, submit requests, and search your embedded knowledge base to help themselves. Below is an overview of the key settings you can customize in the help center:

**Mensagem de login**

Adicione uma mensagem na página de login para dar as boas-vindas ou orientar os clientes durante o processo de login.

[Saiba mais](https://support.atlassian.com/jira-service-management-cloud/docs/add-a-login-message-in-your-help-center/)

**Anúncios**

Os anúncios na página inicial da central de ajuda mantêm os clientes atualizados sobre notícias importantes ou itens relacionados a serviços.

[Saiba mais](https://support.atlassian.com/jira-service-management-cloud/docs/add-an-announcement-to-the-help-center/)

**Aparência**

Customize the look and feel of your help center, including:

- Nome da Central de Ajuda
- Título da página inicial
- Logo
- Banner
- Cor do plano de fundo, link e botão do banner
- Cor do texto do banner da central de ajuda

[Saiba mais](https://support.atlassian.com/jira-service-management-cloud/docs/brand-your-help-center/)

**Layout da página inicial**

Customize how your portals are displayed in your help center. Organize and feature your portals to make sure that your customers can find what they’re looking for. You can also sort your remaining portals by popularity or name.

[Saiba mais](https://support.atlassian.com/jira-service-management-cloud/docs/edit-the-home-page-layout-in-your-help-center/)

**Para alterar qualquer um dos itens acima:**

1. Vá para **Configurações** > **Produtos**.
2. Selecione **Configuração** em **Jira Service Management** no menu lateral.
3. Em **Personalizar central de ajuda**, você vai ver uma lista de opções de personalização disponíveis.
4. Escolha a opção relevante, faça as alterações e selecione **Salvar alterações**.

![Opção de personalização disponível na central de ajuda do Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:c1d87292-ae75-4f34-81b9-a75141101fd1/customize-your-help-center.png?cdnVersion=2537)

[Saiba mais sobre como personalizar a central de ajuda](https://support.atlassian.com/jira-service-management-cloud/docs/customize-the-look-and-feel-of-your-help-center-and-portal/)

**Customize your service project's portal(s)**

Todo projeto de serviço vem com um portal on-line que os clientes usam para interagir com a equipe de atendimento. Esses portais ficam dentro da central de ajuda para que os clientes possam solicitar ajuda de qualquer equipe da sua organização em um local centralizado. Semelhante à central de ajuda, você altera o nome do(s) portal(is), dá as boas-vindas aos clientes com uma introdução e adiciona o logotipo da empresa para refletir sua marca.

**To customize your portal(s):**

1. No menu lateral do projeto de serviço, vá para **Configurações do projeto** > **Configurações do portal**.
2. Edite os campos **Nome**, **Texto de introdução** e **Logotipo** conforme necessário. O logotipo vai aparecer nas notificações enviadas pelo projeto de serviço.

As cores do cabeçalho, URL e botão do portal são herdadas da central de ajuda.

[Saiba mais sobre como personalizar a central de ajuda e o(s) portal(is)](https://support.atlassian.com/jira-service-management-cloud/docs/customize-the-look-and-feel-of-your-help-center-and-portal/)

#### Configure o endereço de e-mail do projeto de serviço

O projeto de serviço vem com um endereço de e-mail na nuvem pré-configurado que você pode enviar aos clientes para uso imediato. Você também pode adicionar um endereço de e-mail personalizado para vincular a uma conta existente (por exemplo, o endereço de e-mail que a equipe de TI usa para solicitações recebidas).

**Para adicionar uma conta de e-mail personalizada para solicitações recebidas:**

1. No menu lateral do projeto de serviço, selecione **Configurações do projeto** > **Solicitações por e-mail**.
2. Escolha o provedor de serviços de e-mail na seção **conectar uma conta de e-mail personalizada** e siga as instruções para vincular a conta.

[![video thumbnail](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJCAYAAAA7KqwyAAAAAXNSR0IArs4c6QAAAAlwSFlzAAALEwAACxMBAJqcGAAAAVlpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IlhNUCBDb3JlIDUuNC4wIj4KICAgPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4KICAgICAgPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIKICAgICAgICAgICAgeG1sbnM6dGlmZj0iaHR0cDovL25zLmFkb2JlLmNvbS90aWZmLzEuMC8iPgogICAgICAgICA8dGlmZjpPcmllbnRhdGlvbj4xPC90aWZmOk9yaWVudGF0aW9uPgogICAgICA8L3JkZjpEZXNjcmlwdGlvbj4KICAgPC9yZGY6UkRGPgo8L3g6eG1wbWV0YT4KTMInWQAAABFJREFUKBVjYBgFoyFAhRAAAAJJAAFEkgypAAAAAElFTkSuQmCC)](https://www.youtube.com/watch?v=PIuvrYFT7q4)

[Saiba mais sobre como receber solicitações de um endereço de e-mail](https://support.atlassian.com/jira-service-management-cloud/docs/receive-requests-from-an-email-address/)

### Etapa 2 - Configure os tipos de solicitação e personalize as filas

#### Configure os tipos de solicitação

Request types help you define and categorize incoming requests and allow you to collect the information you need to resolve them. Your service project comes with default request types based on the project template that was used to create it. You can customize these and add more to suit the needs of your customers and team.

Request types can be organized into portal groups to make it easy for customers to seek the help they need. Below you can see an example of an HR service portal with request types for new employee orientation, onboarding, offboarding, internal transfers, training, and much more.

![Portal de serviço de exemplo do Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:250f004f-2a50-4a4c-8df4-290fa66064c2/set-up-your-request-types.png?cdnVersion=2537)

**Para criar um novo tipo de solicitação:**

1. From the navigation on the left, select **Project settings**, then **Request types**
2. Selecione **Criar tipo de solicitação**.

From here, you can select **Create custom** to build your own request type, or select **Create from template** to use templates designed for different teams and use cases to quickly create a new request type that you can edit later.

**Create custom**

1. Select **Create custom**.
2. Enter the request type name, description, icon, and [issue type](https://confluence.atlassian.com/servicedeskcloud/issue-types-1097176086.html), then select **Next**.
3. Select a portal group, create a new portal group, or leave the checkbox unselected to hide this request type from your portal, then select **Create**.

**Create from template**

1. Browse, search, and **Preview** the different templates.
2. **Select** the template you want to use to create your new request type.
3. Review and update the request type’s details including name, description, icon, portal group, and issue type and associated workflow, then select **Save**.

For both these methods, the request type object will be created and associated with the selected issue type and workflow.

You’ll then need to determine what fields will be displayed to both your customers and your agents. You can customize each request type to show different fields and collect the exact information your team needs to succeed.

**To edit a request type, including fields available in the agent and customer views:**

1. From the navigation on the left, select **Project settings**, then **Request types**

2. Select the request type you want to edit.

3. In the

    

   Request form

    

   tab you can manage the fields that your help seekers will see and fill in when they raise a request in the portal.

   1. Drag and drop from the panel on the right to add new fields, search for fields already used on your site, or create a new custom field. You can add instructions for fields, mark them as required, or assign preset values.
   2. Search and attach existing forms to the request type by selecting **Add form**, selecting the form you want to use from the dropdown list, then selecting **Add**. If no forms exist, navigate to **Project settings** and then **Forms** to create the forms you need.

4. In the **Issue view** tab you can manage the fields that your agents will see – the fields that are visible to them only, as well as the fields help seekers will see on the request form. Drag and drop from the panel on the right to add new fields, search for fields already used on your site, or create a new custom field. Reorder the fields, or drag fields to **Hidden when empty** to change to agent’s view of the issue.

[![video thumbnail](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAJCAYAAAA7KqwyAAAAAXNSR0IArs4c6QAAAAlwSFlzAAALEwAACxMBAJqcGAAAAVlpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IlhNUCBDb3JlIDUuNC4wIj4KICAgPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4KICAgICAgPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIKICAgICAgICAgICAgeG1sbnM6dGlmZj0iaHR0cDovL25zLmFkb2JlLmNvbS90aWZmLzEuMC8iPgogICAgICAgICA8dGlmZjpPcmllbnRhdGlvbj4xPC90aWZmOk9yaWVudGF0aW9uPgogICAgICA8L3JkZjpEZXNjcmlwdGlvbj4KICAgPC9yZGY6UkRGPgo8L3g6eG1wbWV0YT4KTMInWQAAABFJREFUKBVjYBgFoyFAhRAAAAJJAAFEkgypAAAAAElFTkSuQmCC)](https://www.youtube.com/watch?v=A-rLFdXk8UE)

Nota: em projetos gerenciados pela empresa, cada tipo de solicitação é associado a um tipo de item. Esses tipos de item podem ser compartilhados entre projetos no site do Jira. **Os campos de tipo de solicitação e fluxos de trabalho disponíveis são baseados nos campos e fluxos de trabalho do tipo do item associado**.

Em projetos gerenciados pela equipe, cada projeto tem tipos próprios de solicitação que não podem ser compartilhados entre projetos. Essa ação significa que cada projeto gerenciado pela equipe tem tipos próprios de solicitação que são independentes de outros projetos e não estão associados a um tipo de item.

[Saiba mais sobre como categorizar as solicitações dos clientes em tipos de solicitação](https://support.atlassian.com/jira-service-management-cloud/docs/categorize-customer-requests-into-request-types/)

**To edit or change a workflow for a request type:**

1. From the navigation on the left, select **Project settings**, then **Request types**. Select the **More menu** next to the request type you want to update.
2. To edit a workflow, select **View and edit workflow**. Select **Edit workflow**, make your changes then select **Publish**.
3. To replace a workflow, in the Workflow section:
   1. select **Replace using template**, which will enable you to create a new pre-configured workflow from a template and link it to your request type. **Preview** a template to see its description, statuses, and transitions. **Select** the template you want to use, then review and make desired changes to the names of your new workflow and issue type. Select **Continue** and the new workflow and issue type will be added to your project and linked to the request type you chose to update.
   2. or select **Replace with existing**. Choose the workflow you want to use then select **Update**.
4. These options for editing or replacing a workflow can also be accessed from a specific request type's configuration screen. Select **Manage workflow**, then select the option you require.

#### Otimize as filas

Quando os clientes do projeto de serviço criam uma solicitação, essa solicitação vira um item em uma fila. As filas ajudam você a fazer a triagem automática de itens, organizar a forma como os itens aparecem para a equipe e destacar os itens nos quais a equipe deve trabalhar primeiro com base nos [SLAs](https://support.atlassian.com/jira-service-management-cloud/docs/create-service-level-agreements-slas/). A equipe pode ver quantos itens existem em cada fila e alternar entre filas para trabalhar nos itens certos no momento certo.

O Jira Service Management vem com filas padrão que os administradores do projeto podem atualizar para se alinhar à maneira como as equipes fazem a triagem e trabalham nas solicitações dos clientes.

**Para acessar as filas:**

1. No menu lateral do projeto de serviço, vá para **Filas**.
2. Alterne entre filas no menu lateral as selecionando.

**Organize as filas:**

As filas também podem ser organizadas em três seções para manter o espaço de trabalho organizado:

- Marcar como favorito: marcar uma fila ajuda você a escolher a dedo as filas favoritas, fazendo acesso rápido a partir do projeto de serviço. As filas favoritas aparecem apenas na sua exibição e não vão afetar o trabalho da equipe.
- Prioridade da equipe - filas essenciais para os negócios para os agentes verem o tempo todo.
- Outros - as filas são recolhidas neste grupo, mas os agentes podem marcar com estrela para fazer a fixação no lugar.

![Exemplo de fila personalizada no Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:25b04432-6633-4b49-8a03-047ea99595fe/customize-your-queues.png?cdnVersion=2537)

**Para organizar filas:**

1. No menu lateral do projeto de serviço, vá para **Filas**.
2. Selecione **Gerenciar filas**.
3. Arraste e solte as filas entre os dois grupos: **Prioridade da equipe** e **Outros**.
4. Selecione **Fechar**.

![Tela gerenciar filas no Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:1094a757-aea2-4aab-98c3-f8934aa00092/to-arrange-queues.png?cdnVersion=2537)

Para marcar uma fila com estrela, basta passar o mouse sobre a fila escolhida e selecionar o ícone de estrela

#### Criar nova fila

Como a gente já mencionou, o Jira Service Management vem com um conjunto de filas prontas para uso que a equipe pode usar e você pode [editar as filas padrão](https://support.atlassian.com/jira-service-management-cloud/docs/edit-queues/) para exibir itens com base nas preferências.

O Jira Service Management também permite que você crie filas próprias para atender às suas necessidades. Elas podem ser configuradas para mostrar solicitações específicas com base no tipo, status ou algo mais específico usando uma [instrução de linguagem de consulta do Jira](https://support.atlassian.com/jira-service-management-cloud/docs/use-advanced-search-with-jira-query-language-jql/).

**Para criar uma nova fila:**

1. No menu lateral do projeto de serviço, vá para **Filas**.
2. Selecione **Gerenciar filas** na barra lateral de navegação.
3. Selecione **Criar nova fila**.
4. Insira um nome para a fila.
5. Na seção *Filtrar por*, selecione o tipo, o status, a resolução e o rótulo do item nos menus suspensos. Você também pode selecionar **Avançado** para inserir uma [instrução JQL](https://support.atlassian.com/jira-service-management-cloud/docs/use-advanced-search-with-jira-query-language-jql/).
6. Se necessário, selecione os critérios no menu suspenso **Mais**.
7. Se necessário, selecione um pedido no menu suspenso **Pedir por**.
8. Na *seção Colunas*, atualize as colunas arrastando e soltando para o local pretendido. Essa é a ordem das colunas que aparecem na fila.
9. Selecione **Criar**.

![Criar nova fila no Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:b4ab008e-0cf3-45b4-bd60-517504349860/new-queue.png?cdnVersion=2537)

[Saiba mais sobre como fazer a triagem de solicitações de clientes para os agentes com filas](https://support.atlassian.com/jira-service-management-cloud/docs/triage-customer-requests-for-your-agents-with-queues/)

### Etapa 3 - Adicione os membros da equipe e clientes ao projeto de serviço

#### Adicione membros da equipe ao projeto

Hora da festa! Quando tiver configurado o projeto, comece a convidar membros da equipe. Para envolver a equipe, comece adicionando cada membro da equipe como agente no projeto de serviço.

**Para adicionar membros da equipe:**

1. No menu lateral do projeto de serviço, vá para **Convidar equipe**.
2. Insira o(s) e-mail(s) dos usuários que você gostaria de adicionar como agente.
3. Selecione **Convidar**.
4. O agente é adicionado à função **Equipe de projeto de serviço** e recebe um e-mail com um link para o projeto de serviço.

![Convidar membros da equipe para o projeto no Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:4d974412-f84e-4dfe-aba1-6e8858f70c58/add-team-members.png?cdnVersion=2537)

#### Adicionar clientes ao projeto

Next, let’s add customers to your newly created service desk. Customers are people who request help from your service project. You don’t need to add customers to your service project right away, but it’s important to learn how to add them.

Tanto os administradores quanto os agentes do projeto de serviço podem adicionar clientes a um projeto de serviço.

**Para adicionar clientes:**

1. No menu lateral do projeto de serviço, vá para **Clientes**.
2. Selecione **Adicionar clientes**.
3. Digite o e-mail do cliente. Separe os clientes por vírgulas para adicionar mais de um de cada vez.
4. Adicione o cliente a uma [organização](https://support.atlassian.com/jira-service-management-cloud/docs/group-customers-into-organizations/) (opcional).
5. Selecione **Adicionar**.
6. Os clientes vão receber um e-mail de convite. Acesse as [notificações do cliente](https://support.atlassian.com/jira-service-management-cloud/docs/set-up-notifications-for-your-customers-and-team/) para visualizar ou personalizar o e-mail de convite.

Você também pode configurar o Jira Service Management para permitir que os clientes adicionem a si mesmos. Ou você pode abrir o projeto de serviço para usuários do Jira. [Saiba mais sobre as permissões do cliente](https://support.atlassian.com/jira-service-management-cloud/docs/customer-permissions-for-your-service-project-and-jira-site/).

![Adicionar clientes no Jira Service Management](https://wac-cdn.atlassian.com/dam/jcr:9af5c07e-4fdc-4cee-a12f-91b4b9861be4/add-customers.png?cdnVersion=2537)

Agora que você concluiu o básico, leve o projeto para o próximo nível com a coleção de guias de instruções, explicações e documentos úteis que a gente disponibiliza. Há muito mais para aprender…

1. Confira a [demonstração sob demanda do Jira Service Management](https://www.atlassian.com/br/software/jira/service-management/demo), na qual você pode escolher características específicas nos quais está interessado para uma demonstração personalizada.
2. Confira os outros [guias de produtos do Jira Service Management](https://www.atlassian.com/br/software/jira/service-management/product-guide), que abrangem tudo, desde o básico até as práticas detalhadas.
3. Com o [Jira Service Management para dispositivos móveis](https://www.atlassian.com/br/software/jira/service-management/mobile-app) você oferece um ótimo serviço onde quer que esteja.

##### Sobre o Jira Service Management

Visão geral

[Ler o guia](https://www.atlassian.com/br/software/jira/service-management/product-guide/overview)

##### Introdução

Gerenciamento de solicitações de serviço

[Ler o guia](https://www.atlassian.com/br/software/jira/service-management/product-guide/getting-started/service-request-management)