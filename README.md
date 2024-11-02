📈 Aplicação de Análise de Ações com Streamlit
Este projeto é uma aplicação web para visualização e análise de preços de ações, 
construída com Streamlit e 100% Python. A aplicação permite acompanhar a evolução histórica dos preços
de ações e calcular a performance de uma carteira de investimentos ao longo de um período específico.
Setei um valor inicial de R$1.000,00 para carteira, para poder simular uma performance de ações
selecionada pelo usuário.

📌 Funcionalidades
Visualização de preços históricos de ações: Gráfico interativo para acompanhar o preço dos ativos ao longo do tempo.
Filtro de seleção de ações: Possibilidade de escolher os ativos que serão exibidos na visualização.
Filtro de período: Controle total sobre o intervalo de datas para análise.
Cálculo de performance: Cálculo da performance individual dos ativos e da carteira como um todo, com indicação visual de ganhos ou perdas.

🚀 Tecnologias Utilizadas
Streamlit: Para criação da interface web.
Pandas: Para manipulação e análise de dados financeiros.
yfinance: Para extração dos dados de preços das ações.
Python: Linguagem principal para processamento e análise.

⚙️ Como Executar o Projeto Localmente
Clone este repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/dashboard_acoes_streamlit

Navegue até o diretório do projeto:
cd dashboard_acoes_streamlit

Instale as dependências necessárias:
pip install -r requirements.txt

Execute a aplicação:
streamlit run app.py
Acesse o endereço fornecido pelo Streamlit (geralmente http://localhost:8501) no seu navegador para ver a aplicação em ação.

📂 Estrutura do Projeto
app.py: Arquivo principal da aplicação.
IBOV.csv: Arquivo CSV contendo os códigos das ações do índice IBOVESPA, usado para carregar os tickers das empresas.

requirements.txt: Lista de dependências do Python necessárias para rodar a aplicação.
🔄 Atualização dos Dados
A aplicação utiliza a biblioteca yfinance para buscar dados atualizados dos ativos selecionados, garantindo uma análise mais precisa e atual.

📋 Considerações
Este projeto foi desenvolvido como um estudo e prática em visualização de dados financeiroscom Streamlit e é ideal para quem quer entender mais sobre análise de ações de forma visual e prática.
