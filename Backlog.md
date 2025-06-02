# 📡 Sistema de Gestão de Chamados com IA

Este projeto tem como objetivo automatizar a criação, filtragem e resolução de chamados técnicos utilizando Inteligência Artificial, promovendo agilidade no atendimento e organização no controle de suporte.

---

## ✅ Requisitos Funcionais

### 1. Cadastrar Usuário

#### 1.1 - História de Usuário: Cadastro de Clientes
> Como ADM, quero ser o único a cadastrar clientes no sistema.

- Criar a funcionalidade de cadastro de clientes.
- Restringir acesso ao cadastro apenas para o ADM.
- Validar dados como e-mail, nome e senha.
- Exibir mensagens de erro ou sucesso.

#### 1.2 - História de Usuário: Alterar Senha
> Como ADM, quero poder alterar a senha do usuário quando solicitado, garantindo o controle de acesso ao sistema.

- Criar funcionalidade para alteração de senha.
- Validar os dados da nova senha.
- Exibir mensagens de erro ou sucesso.

---

### 2. Login

#### 2.1 - História de Usuário: Login
> Como usuário, quero logar no sistema para utilizar suas funcionalidades.

- Criar o sistema de login.
- Validar dados de acesso (e-mail, nome e senha).
- Exibir mensagens de erro ou sucesso.

---

### 3. CRUD de Chamados

#### 3.1 - História de Usuário: Criar Chamado
> Como usuário, quero abrir um novo chamado e solicitar suporte.

- Criar o sistema de novo chamado.
- Permitir que o usuário informe título, descrição, categoria e prioridade.
- Exibir mensagens de erro ou sucesso.

#### 3.2 - História de Usuário: Visualizar Chamado
> Como usuário, quero visualizar meus chamados para acompanhar o andamento.

- Permitir visualização de chamados.
- Exibir especificações e status (Aberto, Em andamento, Fechado).

#### 3.3 - História de Usuário: Editar Chamado
> Como usuário, quero editar os chamados criados para facilitar a resolução.

- Permitir edição das especificações.
- Salvar as alterações.
- Exibir mensagens de erro ou sucesso.

#### 3.4 - História de Usuário: Cancelar Chamado
> Como usuário, quero poder cancelar um chamado antes de sua resolução, se necessário.

- Verificar se o chamado está aberto.
- Permitir cancelamento apenas de chamados não resolvidos.
- Exibir mensagem de confirmação.
- Registrar o motivo do cancelamento.

#### 3.5 - História de Usuário: Excluir Chamado
> Como ADM, quero excluir chamados fechados para manter a organização.

- Criar a funcionalidade de exclusão.
- Validar dados do administrador.
- Restringir a funcionalidade somente ao ADM.
- Exibir mensagens de erro ou sucesso.

---

### 4. Filtragem e Resolução de Chamados por IA

#### 4.1 - História de Usuário: Filtragem de Chamados
> Como IA, quero analisar automaticamente os chamados para identificar o problema e sua categoria.

- Criar mecanismo de IA para análise de chamados.
- Exibir retorno da IA com especificações do problema.
- Informar se a IA pode resolver ou se um técnico será necessário.

#### 4.2 - História de Usuário: Resolução por IA
> Como usuário, quero receber uma resolução automática após análise da IA para agilizar o atendimento.

- Criar funcionalidade de sugestão de solução automática.
- Validar a solução antes de encerrar o chamado.
- Encaminhar ao técnico caso a IA não resolva.

---

### 5. Resolução por Técnico

#### 5.1 - História de Usuário: Encaminhamento de Chamados
> Como sistema, quero encaminhar chamados a técnicos quando a IA não conseguir resolvê-los.

- Criar funcionalidade de acionamento de técnico.
- Enviar notificação com o problema e suas especificações.
- Atualizar status para "Aguardando Técnico".

#### 5.2 - História de Usuário: Resolução por Técnico
> Como técnico, quero analisar os chamados encaminhados e registrar a solução.

- Criar interface para visualização dos chamados por técnicos.
- Validar dados de acesso do técnico.
- Permitir registro da solução.
- Exibir mensagens de erro ou sucesso.

---

## 🚫 Requisitos Não Funcionais

### 1. Banco de Dados e Compatibilidade
- O sistema deve ser compatível com **SQL Server**, garantindo integridade e consistência dos dados.

### 2. Inteligência Artificial
- Deve integrar um módulo de IA para triagem automática de problemas e sugestões de soluções.

### 3. Segurança
- As senhas devem ser armazenadas de forma segura, utilizando **hash e criptografia**.
- O campo de senha deve exibir caracteres **mascarados** para impedir visualização por terceiros.

---

## 📌 Tecnologias Utilizadas
- C#
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- Bootstrap
- HTML/CSS
- IA (integração com modelo de linguagem)

