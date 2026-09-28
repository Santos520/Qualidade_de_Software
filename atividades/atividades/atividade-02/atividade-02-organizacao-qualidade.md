# Atividade 2: Organização da Qualidade no LocalEats

## 1. Identificação

**Turma:** Qualidade de Software  
**Equipe:** Individual  
**Data:** 22/09/2026

### Integrantes

| Nome | Usuário no GitHub |
|---|---|
| Matheus Souza dos Santos | @Santos520 |

**Elemento de Competência:** Identificar papéis, responsabilidades e competências relacionadas às atividades de qualidade e testes.

---

## 2. Tarefa 1: Diagnóstico da situação

### 2.1 Problemas organizacionais

| Problema identificado | Possível consequência para o produto ou para a equipe |
|---|---|
| Ausência de revisão formal dos requisitos antes da implementação. | Funcionalidades podem ser desenvolvidas de forma diferente do esperado pelos usuários. |
| Falta de planejamento estruturado dos testes. | Defeitos podem chegar até a versão disponibilizada ao usuário final. |
| Dependência de uma única pessoa para executar todas as atividades do projeto. | Sobrecarga de trabalho e maior possibilidade de erros não identificados. |

### 2.2 Responsabilidade pela qualidade

**A qualidade do LocalEats deve ser responsabilidade exclusiva do profissional de QA? Justifiquem.**

Não. Embora o profissional de QA tenha papel importante na verificação da qualidade, ela deve ser responsabilidade de toda a equipe. Desenvolvedores, analistas e responsáveis pelo produto também participam da definição de requisitos, implementação e validação das funcionalidades, contribuindo diretamente para a qualidade final do sistema.

---

## 3. Tarefa 2: Papéis e competências

| Integrante | Papel analisado | Responsabilidades relacionadas à qualidade | Competências técnicas | Competências comportamentais |
|---|---|---|---|---|
| Matheus Santos | Product Owner | Definir requisitos e critérios de aceitação das funcionalidades. | Levantamento e gestão de requisitos. | Comunicação e tomada de decisão. |
| Matheus Santos | Desenvolvedor | Implementar funcionalidades e corrigir defeitos identificados. | Programação, versionamento e testes unitários. | Organização e resolução de problemas. |
| Matheus Santos | Revisor de Código | Avaliar a qualidade do código e identificar melhorias. | Boas práticas de desenvolvimento e revisão técnica. | Atenção aos detalhes e colaboração. |
| Matheus Santos | QA/Testador | Planejar, executar e registrar testes da aplicação. | Técnicas de teste, elaboração de casos de teste e registro de defeitos. | Pensamento crítico e análise. |

---

## 4. Tarefa 3: Matriz de responsabilidades

| Atividade de qualidade | Product Owner | Desenvolvedor | Revisor de Código | QA/Testador |
|---|:---:|:---:|:---:|:---:|
| Definir critérios de aceitação | A/R | C | I | C |
| Revisar requisitos | A/R | C | I | C |
| Implementar a funcionalidade | I | A/R | C | I |
| Revisar o código | I | C | A/R | I |
| Criar testes unitários | I | A/R | C | I |
| Planejar e executar testes do sistema | C | I | I | A/R |
| Registrar e acompanhar defeitos | I | C | I | A/R |
| Priorizar a correção dos defeitos | A/R | C | I | C |
| Aprovar a disponibilização da versão | A/R | C | C | C |

### 4.1 Lacuna ou conflito encontrado

**Lacuna ou conflito:**

A atividade de testes pode ficar excessivamente concentrada apenas no papel de QA/Testador.

**Consequência:**

Problemas de qualidade podem ser identificados tardiamente, aumentando o esforço de correção e atrasando entregas. A participação dos demais papéis na prevenção de defeitos reduz esse risco.

### 4.2 Práticas de QA recomendadas

| Prática recomendada | Problema que ajuda a resolver | Papéis envolvidos |
|---|---|---|
| Revisão de requisitos antes da implementação | Reduz ambiguidades e interpretações incorretas dos requisitos. | Product Owner, Desenvolvedor e QA/Testador |
| Execução de testes antes da liberação de novas versões | Evita que defeitos conhecidos cheguem ao usuário final. | Desenvolvedor e QA/Testador |

---

## 5. Uso de inteligência artificial

**Ferramenta utilizada:**
ChatGPT.
 
**Como foi utilizada:**
Utilizada como ferramenta de apoio para revisão textual.
 
**Como as respostas foram verificadas:**
As respostas foram elaboradas com base na análise realizada na aplicação LocalEats, utilizando observação direta das funcionalidades e registro das evidências durante os testes executados.
