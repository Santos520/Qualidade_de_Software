# Atividade 1: Fundamentos e Características da Qualidade no LocalEats

## 1. Identificação

**Turma:** Qualidade de Software 
**Equipe:** Individual  
**Data:** 22/09/2026

### Integrantes

| Nome | Usuário no GitHub |
|---|---|
| Matheus Santos | @Santos520 |

**Elemento de Competência:** Compreender os fundamentos de qualidade de software e sua aplicação no desenvolvimento de sistemas.

**Aplicação:** https://local-eats-unisenac.vercel.app/

---

## 2. Tarefa 1: Fundamentos da qualidade

### 2.1 Necessidades explícitas e implícitas

| Tipo | Necessidade | Interessado | Consequência se não for atendida |
|---|---|---|---|
| Explícita | Permitir a busca de restaurantes por meio do campo de pesquisa. | Usuário | Dificuldade para localizar restaurantes desejados. |
| Explícita | Permitir o filtro de restaurantes por categoria culinária. | Usuário | Os resultados ficarão menos organizados e mais difíceis de encontrar. |
| Implícita | Exibir mensagens claras quando nenhuma opção for encontrada. | Usuário | O usuário pode acreditar que o sistema apresentou falha ou que a pesquisa não foi realizada. |
| Implícita | Carregar a interface de forma correta e apresentar os elementos da página inicial. | Usuário | O sistema pode parecer indisponível ou incompleto. |

### 2.2 Questão sobre os fundamentos da qualidade

**Um sistema que implementa todas as funcionalidades explicitamente solicitadas pode, ainda assim, apresentar baixa qualidade? Justifiquem utilizando pelo menos uma necessidade implícita identificada pela equipe.**

Sim. Um sistema pode implementar todas as funcionalidades solicitadas e ainda apresentar baixa qualidade caso não atenda necessidades implícitas dos usuários. Por exemplo, se a aplicação não apresentar mensagens claras quando uma pesquisa não encontrar resultados, o usuário poderá interpretar incorretamente o comportamento do sistema, prejudicando sua experiência de uso.

---

## 3. Tarefa 2: Exploração da aplicação

| Integrante | Funcionalidade | O que foi realizado | O que foi observado | Evidência |
|---|---|---|---|---|
| Matheus Santos | Página inicial | Acesso à página principal da aplicação. | A página foi carregada corretamente, apresentando logotipo, campo de pesquisa, categorias e restaurantes disponíveis. | evidencias/pagina-inicial.png |
| Matheus Santos | Busca de restaurantes | Realizada pesquisa utilizando o termo "Italiana". | O sistema exibiu a mensagem "Nenhum restaurante encontrado." | evidencias/pesquisa-sem-resultado.png |
| Matheus Santos | Filtro por categoria | Selecionada a categoria "Japonesa". | Foram exibidos restaurantes relacionados à categoria selecionada. | evidencias/filtro-japonesa.png |

---

## 4. Tarefa 3: Requisitos e características de qualidade

| Integrante | Requisito de Qualidade | Característica ou subcaracterística | Justificativa | Como avaliar |
|---|---|---|---|---|
| Matheus Santos | A página inicial deve carregar corretamente seus elementos principais. | Usabilidade - Operabilidade | O usuário precisa visualizar os recursos disponíveis assim que acessar a aplicação. | Verificar se logotipo, pesquisa, categorias e restaurantes são exibidos corretamente. |
| Matheus Santos | O sistema deve informar claramente quando uma pesquisa não retornar resultados. | Usabilidade - Feedback ao usuário | O usuário precisa compreender o resultado da pesquisa realizada. | Observar a exibição de mensagem adequada quando nenhuma correspondência for encontrada. |
| Matheus Santos | O filtro de categorias deve apresentar restaurantes compatíveis com a categoria selecionada. | Adequação Funcional | A funcionalidade deve produzir resultados coerentes com a opção escolhida. | Comparar os restaurantes exibidos com a categoria selecionada. |

---

## 5. Uso de inteligência artificial

Ferramenta utilizada:
ChatGPT.
 
Como foi utilizada:
Utilizada como ferramenta de apoio para revisão textual.
 
Como as respostas foram verificadas:
As respostas foram elaboradas com base na análise realizada na aplicação LocalEats, utilizando observação direta das funcionalidades e registro das evidências durante os testes executados.
