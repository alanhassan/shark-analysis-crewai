🦈 Shark Attack Intelligence Analysis (CrewAI)
Este projeto utiliza um ecossistema de agentes de IA para transformar dados brutos de ataques de tubarão em relatórios executivos formatados em PDF. Através da biblioteca CrewAI e LangChain, o sistema automatiza a limpeza, categorização e análise estatística de dados históricos.

🚀 Funcionalidades
ETL Automatizado: Limpeza e pré-processamento de dados históricos (até 2018) utilizando Pandas.

Agentes Inteligentes:

Analista de Dados Sênior: Classifica atividades (ex: Surfing, Swimming) em categorias estruturadas como "Esportes de Prancha" ou "Interação Provocada" usando JSON puro.

Escritor de Relatórios: Redige o relatório, com as metricas e análises definidas pelo usuário.

Geração de PDF: Exportação automática de um relatório executivo formatado com os resultados da análise.

Visualização de Dados: Integração com Matplotlib e Seaborn para análise de tendências.

🛠️ Tecnologias Utilizadas
Linguagem: Python

IA & Agentes: CrewAI, LangChain, OpenAI (GPT-4o-mini)

Análise de Dados: Pandas, Numpy

Visualização: Matplotlib, Seaborn

Exportação: FPDF

📋 Pré-requisitos
Uma chave de API da OpenAI.

O dataset attacks.csv (Global Shark Attack File).

🔧 Instalação e Execução
Clone o repositório:

Bash
git clone https://github.com/alanhassan/shark-analysis-crewai
Instale as dependências:

Bash
pip install pandas crewai langchain_openai langchain_experimental python-dotenv fpdf2 matplotlib seaborn
Configure as variáveis de ambiente: Crie um arquivo .env na raiz do projeto:

Snippet de código
OPENAI_API_KEY=sua_chave_aqui
Execute o Notebook: Abra o shark_report.ipynb e execute todas as células para gerar o relatório.

📊 Estrutura do Projeto
shark_report.ipynb: Notebook principal com a lógica dos agentes e análise.

.env: Arquivo para chaves de API (não incluído no repositório por segurança).

requirements.txt: Lista de dependências do projeto.