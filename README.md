# NLTK Text Analyzer: Análise Fundamental de Vocabulário

## Objetivo do Projeto

Este mini-projeto foi desenvolvido como um desafio prático para consolidar os fundamentos do Processamento de Linguagem Natural (PLN) e a utilização da biblioteca Natural Language Toolkit (NLTK) em Python.

O script realiza uma análise básica de um texto de entrada, aplicando técnicas de pré-processamento e fornecendo métricas sobre a diversidade do vocabulário e os temas centrais (frequência dos radicais).

---

## Funcionalidades (Conhecimentos Aplicados)
O projeto demonstra as seguintes etapas essenciais do pipeline de PLN:

1. **Tokenização**  
   Quebra do texto em palavras (tokens).

2. **Remoção de Stop Words**  
   Filtragem de palavras comuns e irrelevantes (artigos, preposições, etc.) usando a base de dados do NLTK para Português.

3. **Stemming (Radicalização)**  
   Redução das palavras às suas formas radicais (ex: *processamento → process*), utilizando o algoritmo `RSLPStemmer`.

4. **Cálculo da Riqueza Lexical**  
   Métrica simples de diversidade de vocabulário:  
   \[
   \frac{\text{Palavras Únicas}}{\text{Palavras Totais Significativas}}
   \]

5. **Análise de Frequência**  
   Identificação dos radicais mais comuns, sinalizando o foco temático do texto.

---

## Tecnologias

| Recurso | Descrição |
|----------|------------|
| **Linguagem** | Python |
| **Biblioteca Principal** | NLTK (Natural Language Toolkit) |
| **Ambiente** | Google Colab (ou Jupyter Notebook) |

---

## Como Executar o Projeto

O projeto está formatado como um **Notebook** para facilitar a visualização e a execução passo a passo no ambiente Colab.

### Passo a passo:
1. **Acesse o Notebook:**  

  [Clique Aqui para Abrir no GitHub](https://github.com/pedrocarvh/Text-Preprocessing-NLTK/blob/main/NLTK_Text_Analyzer.ipynb)

3. **Execute as Células:**
   - Execute a primeira célula para instalar as dependências:  
     ```python
     !pip install nltk
     ```
   - Faça o download dos recursos de dados (NLTK Data).  
   - Edite a variável `TEXTO_DE_ANALISE` na **Célula 3** com o texto que deseja analisar.  
   - Execute todas as células em ordem.

---

## 💡 Exemplo de Saída
RELATÓRIO DE ANÁLISE DE TEXTO     

[1] Visão Geral do Vocabulário:
 - Palavras Totais (Tokens): 45
 - Palavras Únicas: 20
 - Radicais Únicos: 14
 - Riqueza Lexical (Diversidade): **0.8000**
   *Métrica: Palavras Únicas / Palavras Significativas Totais

[2] Frequência Temática (Top 10 Radicais):
 1. 'prátic': 3 ocorrências
 2. 'nltk': 2 ocorrências
 3. 'pln': 2 ocorrências
 4. 'process': 1 ocorrência
 5. 'lingu': 1 ocorrência
... (e assim por diante)


## 🧑‍💻 Autor
**Nome:** [Pedro Carvalho Almeida]  
**GitHub:** [@pedrocarvh]
