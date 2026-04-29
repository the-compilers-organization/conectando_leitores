# 🟣 Sprint 3 – Gestão de Mudança no Projeto

📅 **Período:** 29/03/2026 a 11/04/2026  
⏱️ **Duração:** 2 semanas  

------------------------------------------------------------------------

## 1️⃣ Descrição da Mudança

Durante o desenvolvimento do sistema, foram identificados diversos bugs críticos (P0) que comprometem a segurança, validação de dados e consistência das regras de negócio.

Esses problemas afetam diretamente funcionalidades essenciais como cadastro, login e gerenciamento de livros.

Diante disso, foi necessária uma mudança no planejamento da Sprint para priorizar a correção desses defeitos antes da evolução de novas funcionalidades.

### 🐞 Bugs identificados

- #79 – Cadastro de usuário permite e-mail duplicado  
- #80 – Senha de usuários armazenada sem criptografia  
- #81 – Livros com status "Trocado" ainda aparecem na lista de disponíveis  
- #82 – Regras de exibição de livros não são respeitadas na listagem  
- #83 – Livro cadastrado não é exibido na lista "Meus Livros"  
- #85 – Campo de login não valida formato de e-mail  
- #86 – Login aceita senha incorreta  
- #87 – Cadastro concluído com campo de título preenchido por espaços  

------------------------------------------------------------------------

## 2️⃣ Impacto no Backlog

A inclusão desses bugs impactou diretamente o Product Backlog:

### 🔹 Histórias de usuário impactadas

- US01 – Cadastro de Usuário  
- US02 – Login do Usuário  
- US03 – Cadastro do Livro  
- US04 – Visualizar Livros  
- US07 – Solicitar Troca de Livro  
- US08 – Aceitar Troca de Livro  
- US09 – Recusar Troca de Livro  
- US11 – Cancelar Troca de Livro  

### 🔹 Ajustes realizados

- Inclusão de bugs como itens prioritários no backlog  
- Atualização de regras de negócio e validações  
- Ajuste nos critérios de aceitação (BDD)  
- Reforço de validações de entrada e segurança  

### 🔹 Impacto nas tasks

- Criação de tasks específicas para correção de bugs  
- Revisão de tasks existentes  
- Inclusão de testes adicionais (unitários e validação de cenários negativos)  
- Priorização de correções antes de novas implementações  

------------------------------------------------------------------------

## 3️⃣ Decisão de Priorização

A equipe decidiu priorizar todos os bugs como **P0 (alta prioridade)**, pois:

- Afetam funcionalidades essenciais do sistema  
- Comprometem a segurança (ex: senha sem criptografia)  
- Quebram regras de negócio (ex: livros trocados visíveis)  
- Geram inconsistência de dados  

A reorganização do backlog incluiu:

- Pausa no desenvolvimento de novas funcionalidades  
- Foco total na correção dos bugs  
- Replanejamento das tasks da sprint  

------------------------------------------------------------------------

## 4️⃣ Justificativa Técnica

A decisão foi baseada nos seguintes fatores:

### ✔ Valor para o usuário
- Garante segurança no sistema (criptografia de senha)  
- Evita erros de uso e inconsistências  
- Melhora a confiabilidade da plataforma  

### ✔ Complexidade de implementação
- Baixa a moderada (validações e correções)  
- Necessidade de ajustes em múltiplos módulos  

### ✔ Dependências técnicas
- Módulo de autenticação (login/cadastro)  
- Módulo de livros (listagem e cadastro)  
- Integração entre regras de negócio e interface  

### ✔ Impacto no cronograma
- Médio impacto  
- Necessário para evitar retrabalho futuro  
- Redução de riscos para próximas sprints  

------------------------------------------------------------------------

## 📊 Resultado Esperado

- Sistema mais seguro (criptografia e validações)  
- Regras de negócio corretamente aplicadas  
- Eliminação de inconsistências na listagem de livros  
- Melhor experiência do usuário  
- Redução significativa de falhas críticas  

------------------------------------------------------------------------

## 📌 Observações

A gestão de bugs durante a Sprint evidencia a importância da adaptação contínua no Scrum, permitindo priorizar qualidade e estabilidade do sistema antes da evolução de novas funcionalidades.
