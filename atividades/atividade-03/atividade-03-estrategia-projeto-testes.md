# Atividade 3: Estratégia e Projeto de Testes do LocalEats

## 1. Identificação

**Turma:** Qualidade de Software  
**Equipe:** Individual  
**Data:** 22/09/2026

### Integrantes

| Nome | Usuário no GitHub |
|---|---|
| Matheus Souza dos Santos | @Santos520 |

**Elemento de Competência:** Planejar e projetar testes selecionando técnicas adequadas.

**Aplicação:** https://local-eats-unisenac.vercel.app/

---

## 2. Tarefa 1: Planejamento dos testes

### 2.1 Objetivo dos testes

Os testes têm como objetivo verificar o correto funcionamento das funcionalidades visíveis da aplicação LocalEats. A avaliação foi realizada por meio da interface da aplicação, observando o carregamento da página inicial, o comportamento da busca de restaurantes e os resultados apresentados após a utilização dos filtros disponíveis.

### 2.2 Escopo

#### Funcionalidades incluídas

| Funcionalidade | O que será verificado |
|---|---|
| Página inicial | Verificar se a aplicação carrega corretamente seus elementos principais. |
| Busca de restaurantes | Verificar o comportamento da pesquisa quando não existem resultados correspondentes. |
| Filtro por categoria | Verificar a exibição dos restaurantes após a seleção de uma categoria disponível. |

#### Funcionalidades não incluídas

| Funcionalidade | Justificativa |
|---|---|
| Funcionalidades administrativas | Não estão acessíveis pela interface disponível para testes. |
| Serviços internos e banco de dados | Não podem ser avaliados sem acesso ao código-fonte. |

### 2.3 Abordagem

| Item | Decisão | Justificativa |
|---|---|---|
| Nível de teste | Teste de Sistema | Os testes foram realizados na aplicação completa. |
| Tipo de teste | Teste Funcional | O objetivo foi verificar o comportamento observado pelo usuário. |
| Perspectiva | Caixa-preta | Não houve acesso ao código-fonte da aplicação. |
| Técnicas utilizadas | Particionamento de equivalência e inspeção funcional | Permitem validar respostas para entradas diferentes e verificar comportamentos observáveis da aplicação. |

### 2.4 Ambiente e responsabilidades

| Item | Definição |
|---|---|
| Ambiente | Navegador web com acesso à internet |
| Aplicação | LocalEats |
| Responsável pelo planejamento | Matheus Santos |
| Responsável pela especificação | Matheus Santos |
| Responsável pela execução | Matheus Santos |

### 2.5 Critérios

| Critério | Definição |
|---|---|
| Entrada | Aplicação disponível e acessível |
| Saída | Casos de teste executados e resultados registrados |
| Suspensão | Ocorrência de falha que impeça a continuidade dos testes |

---

## 3. Tarefa 2: Riscos e técnicas de teste

### 3.1 Análise dos riscos

| ID | Funcionalidade | Risco | Consequência | Probabilidade | Impacto | Prioridade |
|---|---|---|---|---|---|---|
| R01 | Carregamento da página inicial | A interface pode não ser carregada corretamente | Usuário impossibilitado de utilizar o sistema | Média | Alto | Alta |
| R02 | Busca de restaurantes | A busca pode retornar informações incorretas ou não informar adequadamente a ausência de resultados | Usuário recebe informações inconsistentes | Média | Alto | Alta |
| R03 | Filtro por categoria | Os restaurantes exibidos podem não corresponder à categoria selecionada | Usuário encontra resultados incorretos | Média | Médio | Média |

### 3.2 Aplicação das técnicas

#### Técnica 1: Inspeção funcional

**Funcionalidade:** Página inicial

**Risco relacionado:** R01

**Justificativa:**

A inspeção funcional permite verificar se os elementos principais da aplicação são carregados e apresentados corretamente ao usuário.

**Caso derivado:** CT01

#### Técnica 2: Particionamento de equivalência

**Funcionalidade:** Busca de restaurantes

**Risco relacionado:** R02

**Justificativa:**

Permite dividir as entradas da pesquisa em grupos representativos, verificando comportamentos para pesquisas que retornam e pesquisas que não retornam resultados.

**Casos derivados:** CT02 e CT03

---

## 4. Tarefa 3: Casos de teste e rastreabilidade

### CT01 - Carregamento da página inicial

**Funcionalidade:** Página inicial

**Risco relacionado:** R01

**Pré-condição:**  
Aplicação disponível.

**Passos:**

1. Acessar o LocalEats.
2. Aguardar o carregamento da página.

**Resultado esperado:**

- Logotipo exibido.
- Campo de busca disponível.
- Categorias apresentadas.
- Lista inicial de restaurantes carregada.

**Resultado observado:**

Todos os elementos foram exibidos corretamente.

**Evidência:**

```text
evidencias/pagina-inicial.png
