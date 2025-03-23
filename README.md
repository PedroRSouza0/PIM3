# Sistema integrado para a gestão de chamados e suporte técnico baseado em IA - PIM 
O Projeto consiste no desenvolvimento de um sistema help desk que organize as chamadas e as auxilie inicialmente através de sugestões por IA.

## Requisitos
Os Requisitos estão divididos entre funcionais e não funcionais, onde os mesmos representam as funcionalidades do sistema.
### Requisitos Funcionais
1. Cadastrar Usuário

    1.1 - **Histórias de Usuário** - Cadastro de Clientes:

    Como ADM, quero ser o único a cadastrar clientes no sistema.

    - Deve criar a funcionalidade cadastro de clientes.
    - Restringi-la somente ao ADM do sistema.
    - Validar dados, (E-mail, nome, senha).
    - Exibir mensagem de erro ou sucesso.

    1.2 **Histórias de Usuário**: - Alterar Senha.

    Como ADM, quero poder alterar a senha do usuário quando solicitado, garantindo o controle de acesso ao sistema.

    - Criar funcionalidade para a alteração de senha.
    - Validar dados da nova senha.
    - Exibir mensagem de erro ou sucesso.

3. Login

    2.1 - **Histórias de Usuário**: - Login.

    Como Usuário, quero logar no sistema para fazer o uso das funcionalidades.

    - Criar o sistema de Login.
    - Validar dados de cadastro, (E-mail, nome, senha).
    - Exibir mensagem de erro ou sucesso.

4. CRUD de Chamados.

    4.1 - **Histórias de Usuário**: - Criar Chamado

    Como usuário quero utilizar o sistema para abrir um novo chamado e solicitar suporte.

    - Criar o sistema de Novo chamado.
    - Permitir que o usuário infome sobre o chamado. (Título, descrição do problema, categoria e prioridade).
    - Exibir mensagem de erro ou sucesso ao criar o chamado.

    4.2 **Histórias de Usuário**: - Vizualizar Chamado

    Como usuário

3. Gerenciamento de chamados.

    3.1 - **Histórias de Usuário**: Como, usuário quero vizualizar meu chamado para acompanhar o andamento da solicitação.
    
    3.2 - **Histórias de Uusário**: Como, técnico quero vizualizar, atualizar e responder a um novo chamado.

    - Deve exibir a lista de chamados com seu status único (Aberto, Em andamento, Fechado).
    - Técnicos recebem os chamados definidos com status de prioridade (Baixa, Média, Alta, Urgente).
    - Técnicos podem responder, atualizar e fechar um chamado.
    - Usuários podem vizualizar as respostas do técnico.

4. Sugestão de Soluções por IA.

    4.1 **Histórias de Usuário**: Como usúario, quero receber sugestões autómaticas por IA, visando resolver o meu problema sem a necessidade de chamar um técnico.
    4.2 **Histórias de Usuário**: Como técnico, quero receber sugestões da IA para otimizar o resolvendo problemas.

    - A IA deverá entender o problema, sabendo categoriza-lo e resolve-lo com base em situações semelhantes.
    - O usuário poderá ser capaz de responder se a solução funcionou ou não. Podendo acionar um técnico caso a resposta seja não.
    - Os técnicos podem utilizar ou não as respostas de IA. 

### Requisitos não funcionais
    - Compatibilidade com SQL Server.
    - Integração com IA.
    - Segurança dos dados
        - Máscara na senha.
    
