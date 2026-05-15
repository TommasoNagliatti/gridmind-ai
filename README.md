# GridMind AI - Sprint 1

## EV Challenge 2026 - GoodWe + FIAP

---

# Integrantes

| Nome                         | RM     |
| ---------------------------- | ------ |
| Tommaso C. Nagliatti         | 572147 |
| Roberson Reguero Luiz Junior | 573031 |
| Arthur Maziviero Faria       | 573928 |
| Matheus Martins Lacerda      | 570843 |
| Jun Uehara		               | 570537 |
| Felipe de Souza Gallo	       | 569680 |

---

# Link do Repositório GitHub

```text
https://github.com/TommasoNagliatti/gridmind-ai
```

---

# Nome do Projeto

# GridMind AI

### Assistente Inteligente para Gestão de Recarga em Condomínios

---

# Contexto do Problema

Com o crescimento do número de veículos elétricos em ambientes residenciais compartilhados, condomínios começam a enfrentar problemas relacionados à distribuição de potência elétrica, monitoramento das recargas, controle de consumo individual, faturamento e gerenciamento operacional dos carregadores.

Muitos sistemas atuais não possuem mecanismos inteligentes capazes de:

* Organizar sessões de recarga;
* Distribuir potência de forma eficiente;
* Identificar horários de pico;
* Detectar riscos de sobrecarga;
* Auxiliar no faturamento individual;
* Monitorar falhas operacionais;
* Transformar dados energéticos em decisões inteligentes.

Dentro do contexto do EV Challenge 2026, o cenário escolhido foi o EV ChargeOps, focado no gerenciamento compartilhado de carregadores em condomínios residenciais.

---

# Problema Abordado

Condomínios com múltiplos veículos elétricos enfrentam dificuldades no gerenciamento compartilhado de recarga elétrica.

Entre os principais problemas identificados estão:

* Sobrecarga da rede elétrica em horários de pico;
* Falta de controle sobre consumo individual;
* Dificuldade de faturamento entre moradores;
* Ausência de inteligência operacional;
* Falta de monitoramento centralizado;
* Dificuldade para síndicos tomarem decisões baseadas em dados.

---

# Proposta da Solução

O projeto GridMind AI propõe o desenvolvimento de um chatbot inteligente baseado em Inteligência Artificial capaz de auxiliar síndicos, administradores e operadores técnicos no gerenciamento de estações de recarga elétrica em condomínios.

O chatbot será responsável por:

* Responder perguntas sobre consumo energético;
* Analisar sessões de recarga;
* Informar riscos de sobrecarga;
* Auxiliar no faturamento individual;
* Identificar padrões de uso;
* Gerar recomendações operacionais;
* Auxiliar na tomada de decisão.

A solução será integrada a dados simulados de carregadores elétricos e utilizará IA contextualizada para fornecer respostas inteligentes baseadas em informações operacionais reais.

---

# Persona Escolhida

## Persona Principal

### Síndico / Administrador do Condomínio

A escolha da persona foi feita considerando que o síndico é o principal responsável pela gestão operacional da infraestrutura compartilhada de recarga.

O chatbot foi pensado como uma ferramenta operacional real para auxiliar em:

* Gestão energética;
* Monitoramento de carregadores;
* Controle de custos;
* Distribuição de potência;
* Organização das recargas;
* Tomada de decisões.

---

# Objetivos do Chatbot

O GridMind AI possui como principais objetivos:

* Melhorar o gerenciamento de recarga compartilhada;
* Reduzir riscos de sobrecarga elétrica;
* Facilitar o controle de consumo;
* Automatizar consultas operacionais;
* Auxiliar no faturamento energético;
* Oferecer suporte inteligente ao síndico;
* Transformar dados em informações úteis.

---

# Tecnologias Selecionadas

| Tecnologia  | Função                             |
| ----------- | ---------------------------------- |
| OpenAI API  | Processamento de linguagem natural |
| GPT-4o-mini | Modelo de IA utilizado             |
| Python      | Linguagem principal do backend     |
| FastAPI     | Desenvolvimento da API             |
| LangChain   | Orquestração do fluxo do chatbot   |
| PostgreSQL  | Armazenamento de dados             |
| Streamlit   | Interface web do chatbot           |
| GitHub      | Versionamento e documentação       |

---

# Justificativa Técnica

## OpenAI API + GPT-4o-mini

Foi escolhida pela alta capacidade de interpretação contextual, velocidade de resposta e facilidade de integração.

O modelo permite:

* Respostas contextualizadas;
* Interpretação de linguagem natural;
* Geração de recomendações inteligentes;
* Simulação de suporte operacional.

## Python

Python foi escolhido por possuir grande compatibilidade com bibliotecas de IA, APIs e ferramentas de análise de dados.

## FastAPI

FastAPI permite construção rápida de APIs modernas e escaláveis.

## LangChain

Será utilizado para organizar contexto, memória e processamento do chatbot.

## PostgreSQL

Responsável pelo armazenamento de:

* Dados de usuários;
* Sessões de recarga;
* Consumo energético;
* Logs operacionais.

## Streamlit

Foi escolhido por permitir rápida prototipação de interfaces web interativas.

---

# Escopo do Chatbot

O chatbot será responsável por responder perguntas relacionadas ao gerenciamento operacional da infraestrutura de recarga.

Entre as funcionalidades previstas estão:

* Consulta de consumo energético;
* Consulta de sessões de recarga;
* Monitoramento de potência;
* Identificação de horários de pico;
* Recomendações de recarga;
* Simulação de custos;
* Alertas operacionais;
* Identificação de falhas.

---

# Fluxograma de Funcionamento

## Fluxo Geral do Sistema

```text
Usuário
   ↓
Interface do Chatbot (Streamlit)
   ↓
API Backend (FastAPI)
   ↓
Banco de Dados
   ↓
Processamento Contextual
   ↓
LLM OpenAI
   ↓
Geração de Resposta Inteligente
   ↓
Resposta ao Usuário
```

---

# Explicação do Fluxo

## 1. Entrada do Usuário

O usuário realiza uma pergunta relacionada ao sistema de recarga.

Exemplo:

"Existe risco de sobrecarga hoje às 20h?"

## 2. Interface do Chatbot

A interface recebe a pergunta e envia para a API backend.

## 3. Backend

O backend processa a solicitação e consulta os dados relevantes.

## 4. Banco de Dados

São coletadas informações como:

* Histórico de recarga;
* Potência disponível;
* Consumo energético;
* Horários de uso.

## 5. Processamento Contextual

As informações operacionais são organizadas e enviadas ao modelo de IA.

## 6. LLM

O modelo interpreta os dados e gera uma resposta contextualizada.

## 7. Resposta

O usuário recebe uma resposta inteligente baseada nos dados do sistema.

---

# Modelo de Teste

## Teste 1

### Pergunta

"Qual morador consumiu mais energia nesta semana?"

### Resposta Esperada

O chatbot deverá informar:

* Nome do morador;
* Consumo total em kWh;
* Custo estimado;
* Comparação com média semanal.

---

## Teste 2

### Pergunta

"Existe risco de sobrecarga hoje às 20h?"

### Resposta Esperada

O chatbot deverá:

* Verificar sessões agendadas;
* Comparar potência disponível;
* Informar risco operacional;
* Recomendar redistribuição de carga.

---

## Teste 3

### Pergunta

"Quanto o apartamento 82 deve pagar este mês?"

### Resposta Esperada

O chatbot deverá calcular:

* Consumo individual;
* Tarifa aplicada;
* Valor total;
* Histórico mensal.

---

## Teste 4

### Pergunta

"Qual o melhor horário para recarga?"

### Resposta Esperada

O chatbot deverá:

* Identificar horários com menor demanda;
* Sugerir horários econômicos;
* Informar menor risco de sobrecarga.

---

## Teste 5

### Pergunta

"Algum carregador apresentou falha hoje?"

### Resposta Esperada

O chatbot deverá:

* Identificar falhas de comunicação;
* Detectar interrupções;
* Informar carregadores com comportamento anormal.

---

# Contexto-Base (System Prompt)

```text
Você é um assistente inteligente especializado em gerenciamento de recarga de veículos elétricos em condomínios residenciais utilizando infraestrutura GoodWe.

Seu objetivo é auxiliar síndicos, administradores e operadores técnicos na análise de consumo energético, distribuição de potência, identificação de riscos de sobrecarga, faturamento individual e monitoramento operacional dos carregadores.

Você deve responder de forma técnica, objetiva e contextualizada ao ambiente de recarga compartilhada.

Considere sempre:
- Limites de potência do condomínio
- Horários de pico
- Consumo individual por usuário
- Eficiência energética
- Segurança operacional
- Dados simulados de carregamento

Evite respostas genéricas.
Sempre priorize decisões operacionais inteligentes baseadas em dados.
```

---

# Estrutura do Repositório GitHub

```text
/gridmind-ai
│
├── README.md
├── docs
│   ├── fluxograma.png
│   ├── modelo-testes.md
│   └── arquitetura.md
│
├── backend
│   ├── app.py
│   ├── routes.py
│   └── services
│
├── frontend
│   └── streamlit_app.py
│
├── prompts
│   └── system_prompt.txt
│
└── database
    └── mock_data.json
```

---

# Diferenciais da Solução

O GridMind AI se diferencia por:

* Utilizar IA aplicada ao contexto energético;
* Ser focado em operação real;
* Trabalhar com dados contextualizados;
* Auxiliar na tomada de decisão;
* Melhorar a gestão compartilhada;
* Transformar dados em inteligência operacional.

---

# Conclusão

O projeto GridMind AI busca solucionar problemas reais relacionados ao gerenciamento compartilhado de carregadores elétricos em condomínios.

A proposta está alinhada ao contexto do EV Challenge 2026 ao utilizar Inteligência Artificial como elemento central da solução, transformando dados energéticos em decisões operacionais inteligentes.

O chatbot foi projetado não apenas como uma interface conversacional, mas como uma ferramenta operacional capaz de auxiliar síndicos e administradores na gestão eficiente da infraestrutura de recarga elétrica.

---

# Aviso Importante

O projeto apresentado nesta Sprint representa uma visão inicial do GridMind AI. Durante as próximas etapas do EV Challenge 2026, tanto o escopo quanto as tecnologias, integrações e funcionalidades propostas poderão sofrer ajustes e melhorias.

Essas alterações podem ocorrer devido a refinamentos de requisitos, decisões de arquitetura, validações técnicas e evolução natural do desenvolvimento do sistema.

O objetivo desta Sprint é estabelecer a base conceitual, técnica e arquitetural da solução, servindo como referência inicial para as próximas fases do projeto.
