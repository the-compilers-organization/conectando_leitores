# 🟣 Sprint 3 – Gestão de Mudança no Projeto

📅 **Período:** 29/03/2026 a 11/04/2026  
⏱️ **Duração:** 2 semanas  

------------------------------------------------------------------------

## 1️⃣ Descrição da Mudança

Durante o desenvolvimento do sistema, foi identificada a necessidade de melhorar o controle de disponibilidade dos livros no fluxo de trocas.

Foi observado que, ao aceitar ou recusar uma troca, havia risco de inconsistência na exibição dos livros, permitindo que livros indisponíveis aparecessem nas buscas.

Diante disso, foi proposta a seguinte mudança:

👉 Implementar controle rigoroso de status dos livros (Disponível, Em negociação, Trocado)  
👉 Garantir atualização automática do status dos livros conforme ações de troca (aceitar, recusar, cancelar)

------------------------------------------------------------------------

## 2️⃣ Impacto no Backlog

A mudança impactou diretamente o Product Backlog da seguinte forma:

### 🔹 Histórias de usuário modificadas

- US04 – Visualizar Livros  
- US07 – Solicitar Troca de Livro  
- US08 – Aceitar Troca de Livro  
- US09 – Recusar Troca de Livro  
- US11 – Cancelar Troca de Livro  

### 🔹 Ajustes realizados

- Inclusão de validações de status dos livros  
- Atualização dos critérios de aceitação (BDD)  
- Ajuste nas regras de negócio relacionadas à visibilidade dos livros  

### 🔹 Impacto nas tasks

- Criação de novas tasks para validação de status  
- Ajustes em tasks existentes relacionadas à listagem e troca de livros  
- Inclusão de testes adicionais (cenários positivos e negativos)

------------------------------------------------------------------------

## 3️⃣ Decisão de Priorização

A equipe decidiu priorizar essa mudança com alta prioridade (P0), pois impacta diretamente a experiência do usuário e a consistência do sistema.

A reorganização do backlog considerou:

- Ajuste imediato das histórias afetadas  
- Repriorização das tasks relacionadas ao fluxo de troca  
- Garantia de consistência antes da implementação de novas funcionalidades  

------------------------------------------------------------------------

## 4️⃣ Justificativa Técnica

A decisão foi baseada nos seguintes fatores:

### ✔ Valor para o usuário
- Evita confusão ao exibir livros indisponíveis  
- Garante confiabilidade na plataforma  

### ✔ Complexidade de implementação
- Complexidade moderada  
- Necessidade de controle de estado (status)  

### ✔ Dependências técnicas
- Dependência entre módulos de livros e trocas  
- Integração com listagem e notificações  

### ✔ Impacto no cronograma
- Pequeno impacto no prazo  
- Necessário para evitar retrabalho futuro  

------------------------------------------------------------------------

## 📊 Resultado Esperado

- Sistema com controle consistente de status  
- Regras de negócio respeitadas  
- Melhor experiência do usuário  
- Redução de bugs relacionados à troca de livros  

------------------------------------------------------------------------

## 📌 Observações

A gestão de mudanças durante a Sprint demonstra a aplicação prática de metodologias ágeis, permitindo adaptação contínua do sistema conforme novas necessidades identificadas.
