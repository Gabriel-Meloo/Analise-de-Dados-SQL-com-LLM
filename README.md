# 🧠🔍 Chatbot de Análise de Dados SQL com LLM

Este projeto implementa um **chatbot inteligente** que permite aos usuários consultarem e analisarem dados diretamente de um **banco de dados SQL** utilizando **linguagem natural**. 

A aplicação traduz perguntas como “Quais foram as vendas do último trimestre?” em **consultas SQL automáticas**, executa no banco e retorna as respostas de forma clara, podendo inclusive **gerar gráficos personalizados**.

---

## 🎯 Objetivo

Simplificar o acesso a informações armazenadas em bancos de dados relacionais, eliminando a necessidade de escrever queries SQL manualmente. Ideal para equipes de negócios, marketing, financeiro e outras que queiram extrair insights com rapidez e segurança.

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia         | Função                                                 |
|--------------------|--------------------------------------------------------|
| **Python 3.10+**   | Linguagem base do projeto                              |
| **Groq API**       | Execução do LLM (ex: LLaMA 3, Mixtral)                 |
| **LlamaIndex**     | Conexão entre linguagem natural e estrutura dos dados  |
| **Gradio**         | Interface gráfica acessível via navegador              |
| **SQLAlchemy**     | Abstração e conexão com banco de dados                 |
| **Pandas**         | Manipulação de resultados das queries                  |
| **Matplotlib / Seaborn** | Visualização de dados                           |

---

## 🧠 Funcionamento

1. O usuário faz uma pergunta em **linguagem natural** (ex: "Qual foi o total de pedidos por mês em 2024?")
2. O sistema usa o **LLM via Groq** para gerar a query SQL correspondente
3. A query é **executada em tempo real** no banco de dados
4. A resposta é retornada em formato legível, podendo incluir **tabelas ou gráficos**

---

## 🛠️ Requisitos

- Acesso a um banco SQL (PostgreSQL, MySQL, SQLite, etc.)
- Chave de API da Groq
- Python 3.10 ou superior
