Dashboard de Ansiedade

Este projeto é uma aplicação interativa desenvolvida com o Streamlit, permitindo visualizar e analisar fatores que impactam a ansiedade. Com base nos dados inseridos, o sistema retorna informações detalhadas e gráficos interativos para melhor compreensão dos padrões de ansiedade.

🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

📋 Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

Python: versão 3.8 ou superior.

🛠️ Bibliotecas Utilizadas

Este projeto utiliza as seguintes bibliotecas:

Streamlit: Para criar interfaces web interativas de forma simples.

pandas: Para manipulação e análise de dados.

numpy: Para cálculos estatísticos e manipulações numéricas.

plotly: Para gerar gráficos interativos e visualizações dinâmicas.

requests: Para consumo de APIs externas, se necessário.

🔧 Instalação

Siga estas etapas para configurar o ambiente:

Clone o repositório:

git clone https://github.com/seu_usuario/Ansiedade_dash.git

Acesse o diretório do projeto:

cd monitoramento-ansiedade

Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate

Instale as dependências:

pip install -r requirements.txt

Execute a aplicação:

streamlit run main.py

Abra o navegador e acesse http://127.0.0.1:8501 para visualizar a aplicação.

📈 Funcionalidades

Monitoramento Interativo: Insira os dados e obtenha insights sobre padrões de ansiedade.

Gráficos Dinâmicos: Visualize fatores que influenciam a ansiedade através de gráficos de radar e dispersão.

Análise de Tendências: Compare valores e veja a evolução dos indicadores ao longo do tempo.

🎨 Personalizações

Interface Customizada: A aplicação conta com um design limpo e intuitivo para melhor experiência do usuário.

Visualizações Gráficas: Gráficos interativos tornam a análise mais acessível e fácil de entender.

📸 Exemplos Visuais

Abaixo estão exemplos dos gráficos gerados pela aplicação:

Gráfico de Radar: Exibe a influência de diferentes fatores sobre a ansiedade.

Gráficos de Linha e Dispersão: Mostram a evolução dos níveis de ansiedade ao longo do tempo.

📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
