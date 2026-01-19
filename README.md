# [WIP] aprimoramento_planilhas
## Limpeza, classificação e união de planilhas
*O repositório tem como objetivo o tratamento de planilhas utilizando de automações. Os dados utilizados para criar o código vieram de um Scrapping feito no Google utilizando palavras-chave
O repositório acadêmico ao qual o código está vinculado se chama "Projeto Fogo na Fake", que tem como intuíto analisar a propagação de fake news relacionadas com o Cerrado, instruir e conscientizar o público quanto à esse problema*
**O repositório é capaz de:**
 - Treinar um modelo de classificação de texto e, subsequentemente, utilizá-lo para classificar em lote outros arquivos, visando automatizar a marcação e a revisão de documentos com base na presença ou ausência de um critério 'X'. As bibliotecas chave empregadas são pandas para manipulação de dados em CSV/Excel; os para gerenciamento de arquivos e diretórios; joblib para salvar e carregar o modelo e o vetorizador; datetime para versionamento de arquivos; e sklearn (com TfidfVectorizer e LogisticRegression) para a vetorização do texto e o treinamento do modelo de classificação, além de re para limpeza de texto. O processo envolve a configuração inicial de variáveis, o treinamento do modelo com dados existentes e, finalmente, a aplicação desse modelo para classificar novos arquivos, gerando saídas com status de revisão em uma pasta de resultados..
 - Automatizar a limpeza de arquivos Excel: ele se conecta ao seu Google Drive, localiza os arquivos 'conteudo*.xlsx' ainda não processados, e então, para cada um, lê seus dados, saneia textos, filtra linhas com 'x' na coluna 'marcacao_X' e remove colunas específicas (var1, var2, var3), salvando o resultado como um novo arquivo _limpo.xlsx. Para isso, utiliza google.colab para integração com o Drive, os e glob para manipulação de arquivos, pandas como ferramenta principal de processamento de dados (leitura, filtragem, transformação, escrita), e re para operações de saneamento de texto..
 -  Utilizar as bibliotecas google.colab para montar seu Google Drive e acessar arquivos, pandas para manipular dados e os para interagir com o sistema operacional. Sua principal função é consolidar múltiplos arquivos Excel de um diretório específico, renomeando as colunas e removendo linhas indesejadas, para depois salvar o conjunto de dados limpo e combinado em um novo arquivo CSV.
# Arthur Santos | Analista de Dados Jr

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/arthurfs)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/arthurfs0)
[![Portfólio](https://img.shields.io/badge/Portfólio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://seu-portfolio.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthurofscg@gmail.com)

## 📊 Sobre Mim

Profissional em transição para **Análise de Dados**, com experiência sólida em **gestão, organização e tratamento da informação**
em instituições públicas de alta complexidade, como **STF, STJ e Senado Federal**.

Atuo com **Python, SQL e Power BI** na coleta, limpeza, organização e análise de dados,
transformando dados brutos em informações estruturadas para apoio à tomada de decisão,
com foco em qualidade, consistência e clareza na comunicação com áreas de negócio.

**Formação:** Graduando em Biblioteconomia e Arquivologia – Universidade de Brasília  
**Foco atual:** Análise de Dados, Business Intelligence e Data Storytelling

## 🛠 Habilidades Técnicas

### Linguagens & Ferramentas

- Python  
- SQL  
- Power BI  
- Excel  
- Pandas  
- NumPy  

### Áreas de Conhecimento

- Análise Exploratória de Dados (EDA)  
- Visualização de Dados & Dashboarding  
- Data Cleaning & Preprocessing  
- Business Intelligence  
- Gestão e Qualidade de Dados  
- Storytelling com Dados  

## 📈 repositórios em Destaque

### 1. Análise de Dados Abertos do Judiciário

Análise de datasets públicos do sistema judiciário brasileiro,
com foco em identificação de padrões, tendências e indicadores relevantes.

---

### 2. Dashboard de Monitoramento Institucional (repositório Acadêmico)

Desenvolvimento de dashboard completo para acompanhamento de indicadores,
apoio à tomada de decisão e visualização de métricas estratégicas.

---

### 3. Data Cleaning com Python – Dataset Governamental

Pipeline completo de limpeza, padronização e validação de dados públicos,
garantindo qualidade e consistência das informações analisadas.
