# Sistema integrado para a gestão de chamados e suporte técnico baseado em IA - PIM 
O Projeto consiste no desenvolvimento de um sistema help desk que organize as chamadas e as auxilie inicialmente através de sugestões por IA.

## Requisitos
Os Requisitos estão divididos entre funcionais e não funcionais, onde os mesmos representam as funcionalidades do sistema.
### Requisitos Funcionais
1. Cadastrar Usuário

    1.1 - **Histórias de Usuário**: Como, Usuário quero me cadastrar no sistema para abrir chamados.

    - Deve permitir o cadastro com nome, e-mail e senha.
    - Deve-se validar e-mail.
    * Deve-se permitir recuperação de senha.

100. Criação de chamados.

    2.1 - **Histórias de Usuário**: Como, usuário quero utilizar o sistema para solicitar ajuda detalhando o meu problema através de chamados.

    - Deve permitir vizualizar o chamado criado
    - Deve registrar as informações do usuário solicitador
    - O usuário deve especificar o nível de prioridade do chamado (Baixa, Média, Alta, Urgente).

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
    