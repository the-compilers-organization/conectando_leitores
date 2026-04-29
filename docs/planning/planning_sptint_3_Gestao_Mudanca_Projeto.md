# 🟣 Sprint 3 – Gestão de Mudança no Projeto

📅 **Período:** 29/03/2026 a 11/04/2026  
⏱️ **Duração:** 2 semanas  

------------------------------------------------------------------------

## 1️⃣ Objetivo da Sprint

Corrigir bugs críticos (P0) identificados no sistema Conectando Leitores, garantindo segurança, consistência de dados e estabilidade da aplicação antes da evolução de novas funcionalidades.

------------------------------------------------------------------------

## 2️⃣ Descrição da Mudança

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

## 3️⃣ Impacto no Backlog

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
- Inclusão de testes adicionais (unitários e cenários negativos)  
- Priorização de correções antes de novas implementações  

------------------------------------------------------------------------

## 4️⃣ Decisão de Priorização

A equipe decidiu priorizar todos os bugs como **P0 (alta prioridade)**, pois:

- Afetam funcionalidades essenciais do sistema  
- Comprometem a segurança (ex: senha sem criptografia)  
- Quebram regras de negócio  
- Geram inconsistência de dados  

A reorganização do backlog incluiu:

- Pausa no desenvolvimento de novas funcionalidades  
- Foco total na correção dos bugs  
- Replanejamento das tasks da sprint  

------------------------------------------------------------------------

## 5️⃣ Justificativa Técnica

### ✔ Valor para o usuário
- Garante segurança no sistema  
- Evita inconsistências  
- Melhora a confiabilidade  

### ✔ Complexidade
- Baixa a moderada  
- Correções distribuídas em múltiplos módulos  

### ✔ Dependências
- Autenticação (login/cadastro)  
- Módulo de livros  
- Regras de negócio  

### ✔ Impacto no cronograma
- Médio impacto  
- Redução de riscos futuros  

------------------------------------------------------------------------

## 6️⃣ Estimativas

As estimativas foram definidas considerando a correção dos bugs críticos:

- Correção de bugs P0 (8 bugs) → **8 pontos**
- Ajustes de validação e segurança → **3 pontos**
- Revisão de regras de negócio → **3 pontos**

**Total estimado: 14 pontos**

------------------------------------------------------------------------

## 7️⃣ Registro das Daily Scrums

As reuniões diárias ocorreram durante toda a Sprint.

Cada daily seguiu o padrão:

- O que foi feito  
- O que será feito  
- Impedimentos  

Resumo:

- Identificação e análise dos bugs  
- Correção das falhas críticas  
- Ajustes de validações e regras de negócio  
- Revisão de funcionalidades impactadas  
- Testes manuais e validação das correções  

📂 Registros completos disponíveis em:
docs/daily/sprint_3

------------------------------------------------------------------------

## 8️⃣ Incremento da Sprint

Ao final da Sprint 3, foram entregues:

- Correção dos 8 bugs críticos identificados  
- Implementação de criptografia de senha  
- Validação de e-mail no login e cadastro  
- Correção das regras de exibição de livros  
- Ajustes na listagem e cadastro de livros  
- Sistema mais estável e consistente  

------------------------------------------------------------------------

## 9️⃣ Retrospectiva da Sprint

### ✔ O que funcionou bem

- Identificação rápida dos bugs críticos  
- Priorização eficiente  
- Boa adaptação à mudança  
- Comunicação clara  
- Uso das dailys para acompanhamento  

### ⚠️ O que não funcionou bem

- Bugs não identificados anteriormente  
- Falta de validações desde o início  
- Ausência de testes automatizados  
- Retrabalho  
- Impacto no cronograma  

### 🔧 Melhorias

- Implementar testes automatizados  
- Refinar critérios de aceitação  
- Melhorar revisão de código  
- Validar antes de avançar  

### 🚀 Ações para próxima Sprint

- Adotar testes automatizados  
- Garantir cobertura de cenários negativos  
- Revisar validações  
- Melhorar refinamento das histórias  

📂 Registros completos disponíveis em:
docs/retrospective/retrospectiva_sprint_3.md

------------------------------------------------------------------------

## 📊 Resultado da Sprint

- Bugs críticos corrigidos ✔  
- Sistema mais seguro ✔  
- Regras de negócio ajustadas ✔  
- Estabilidade aumentada ✔  

------------------------------------------------------------------------

## 📌 Observações

Esta Sprint evidenciou a importância da adaptação no Scrum e da priorização da qualidade do sistema antes da evolução de novas funcionalidades.