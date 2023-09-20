
![cripto](https://livecoins.com.br/wp-content/uploads/2021/10/Diferentes-criptomoedas-na-mao-com-lupa-696x385.jpg)

# <center> <font color = 'bluegreen'> Criptomoedas </font> </center>


## <center> <font color = 'grey'> Análise exploratória histórica dos valores </font> </center>

Este projeto foi desenvolvido pelo Squad 2 do Módulo 5 do curso Data Analytics da Resília Educação em parceria com o iFood. Aplicando a Metodologia Ágil Scrum e a organização por funções proposto pela Resília, seguem os papéis desempenhados:

[José Wedson](https://www.linkedin.com/in/wedson-tavares-0a7961261/) - Product Owner / Co-Facilitador

[Marcos Retondar](https://www.linkedin.com/in/marcos-retondar/) - Scrum Master / Gestor de Conhecimento

[Pâmela Carvalho Sousa](https://www.linkedin.com/in/pamela-carvalho-tech-analista-dados-jr/) - Equipe de Desenvolvimento / Gestora de Gente e Engajamento

[Luciana Nunes](https://www.linkedin.com/in/luhonunes/) - Equipe de Desenvolvimento / Colaboradora



As criptomoedas representam uma inovação revolucionária no mundo financeiro, introduzindo um paradigma descentralizado e seguro para transações digitais. Baseadas em tecnologia de blockchain e criptografia, essas moedas digitais têm impactado de maneira significativa a economia global e a forma como concebemos as finanças.

Este relatório tem como objetivo conduzir uma análise exploratória histórica dos valores das criptomoedas. A análise se baseia em uma série temporal abrangente que se estende desde 29 de abril de 2013 até 06 de julho de 2021. Essa investigação meticulosa visa compreender as tendências, volatilidade e desempenho desses ativos digitais ao longo de um período de tempo substancial.

Neste relatório, adotaremos uma abordagem rigorosa de análise de dados e apresentaremos visualizações e conclusões significativas para cada uma das questões abordadas. Por meio dessa exploração profunda, esperamos contribuir para uma compreensão mais abrangente e fundamentada do mercado de criptomoedas e seu impacto no cenário financeiro global.

---

## <center> <font color = 'bluegreen'> **Objetivo da Análise** </font> </center>

O objetivo deste trabalho é compreender as tendências, volatilidade e desempenho das criptomoedas ao longo de um período de tempo substancial, que se estende de 29 de abril de 2013 até 06 de julho de 2021. Esta análise visa fornecer insights valiosos para investidores e corretoras no mercado de criptomoedas, além de responder alguns questionamentos e fornecer infomações de alto valor para investidores, entusiastas e profissionais da área.

---

## <center> <font color = 'bluegreen'> **Fontes de Dados** </font> </center>

Os dados utilizados nesta análise foram obtidos a partir do conjunto de dados **"Cryptocurrency Price History"** hospedado no Kaggle. Este conjunto de dados é mantido por [Udalai Rajkumar](https://www.kaggle.com/udalairajkumar) e pode ser encontrado no seguinte link: [Cryptocurrency Price History on Kaggle](https://www.kaggle.com/udalairajkumar/cryptocurrencypricehistory).

O conjunto de dados inclui informações detalhadas sobre os preços históricos de várias criptomoedas ao longo do tempo, o que nos permitiu realizar uma análise exploratória abrangente.

Para acessar os dados utilizados nesta análise, você pode visitar o link fornecido acima e seguir as instruções de download fornecidas pelo autor no Kaggle.

---

## <center> <font color = 'bluegreen'> **Estrutura dos Dados** </font> </center>

O conjunto de dados fornecido é uma compilação abrangente e detalhada das informações históricas relacionadas a várias criptomoedas ao longo de um período de tempo significativo, abrangendo desde 29 de abril de 2013 até 06 de julho de 2021. Este dataset apresenta informações essenciais para analisar o comportamento dessas moedas digitais, incluindo seus preços máximos e mínimos diários, valores de abertura e fechamento, volume de negociação e capitalização de mercado. Cada linha do dataset representa um ponto de dados único, permitindo uma análise granular das tendências de mercado e do desempenho individual de cada criptomoeda. Com esses dados em mãos, é possível realizar uma análise exploratória completa e identificar insights valiosos sobre a dinâmica do mercado de criptomoedas durante o período considerado.

---

![Criptomoedas](https://github.com/luhonunes/Criptomoedas_Resilia/blob/main/Imagens_Relat%C3%B3rio/Tendencias.png?raw=true)

---

## <center> <font color = 'bluegreen'> **Métodos Utilizados** </font> </center>

Nossa análise exploratória de criptomoedas foi conduzida seguindo uma série de etapas bem definidas, visando garantir a qualidade dos resultados e insights obtidos. Abaixo, descrevemos sucintamente as etapas que seguimos:

- **Coleta e Importação de Dados:** 

    Utilizamos o conjunto de dados "Cryptocurrency Price History" hospedado no Kaggle, mantido por [Udalai Rajkumar](https://www.kaggle.com/udalairajkumar). Importamos esses dados em nosso ambiente de análise para começar nossa exploração.

- **Limpeza e Pré-processamento:**

    Realizamos uma limpeza detalhada dos dados, tratando valores ausentes, eliminando duplicatas e garantindo que os tipos de dados estavam corretos para cada coluna. Também verificamos se não havia outliers que poderiam distorcer nossas análises.

- **Cálculos e Derivação de Novas Variáveis:**

    Calculamos métricas relevantes para nossa análise, como médias móveis, retornos diários, e outras estatísticas que nos ajudaram a entender melhor o comportamento das criptomoedas.

- **Visualizações Gráficas:**

    Utilizamos bibliotecas como Matplotlib, Seaborn e Plotly para criar os gráficos iniciais e ter uma métrica dos dados a serem analisados, incluindo gráficos de linha para acompanhar as tendências de preços ao longo do tempo e boxplot para visualizar o comportamento dos valores das criptomoedas.

- **Análise Visual no Power BI:**

    Utilizamos o Power BI para criar visualizações interativas, como gráficos de linha para acompanhar as tendências de preços ao longo do tempo, gráficos de barras para comparar o desempenho de diferentes criptomoedas em relação aos dias da semana e gráficos de calor para explorar correlações. Essas visualizações foram fundamentais para obter insights significativos.

- **Análise de Correlações:**

    Utilizamos ferramentas estatísticas para determinar se havia correlações significativas entre os preços de diferentes criptomoedas.

- **Perguntas Adicionais:**

    Além das questões fundamentais, exploramos perguntas adicionais relacionadas à volatilidade, sazonalidade e influências externas nas criptomoedas. Aplicamos métodos estatísticos relevantes para responder a essas perguntas.

- **Apresentação dos Resultados:**

    Utilizamos formatação em Markdown para criar descrições detalhadas de cada etapa da análise, incluindo explicações dos gráficos e tabelas, e destacamos os insights obtidos.

Ao seguir essas etapas e utilizar as bibliotecas Python, fomos capazes de conduzir uma análise abrangente e precisa das séries temporais de preços das criptomoedas, respondendo às perguntas propostas e explorando as perguntas adicionais de forma eficaz.


- **Apresentação dos Resultados:**

    Utilizamos formatação em Markdown para criar descrições detalhadas de cada etapa, incluindo explicações dos gráficos e tabelas, e destacamos os insights obtidos.

Ao seguir essas etapas, utilizar as bibliotecas Python como Pandas, Numpy, Seaborn, Plotly e Matplotlib e aproveitar as capacidades do Power BI, conseguimos realizar uma análise abrangente e precisa das séries temporais de preços das criptomoedas, respondendo às perguntas propostas e explorando questões adicionais de maneira eficaz.

---

## <center> <font color = 'bluegreen'> **Tecnologias e Ferramentas Utilizadas** </font> </center>

Neste projeto, empregamos uma ampla gama de tecnologias e ferramentas que desempenharam papéis cruciais em nossa análise exploratória da série temporal de preços das criptomoedas. As seguintes tecnologias e recursos foram fundamentais para o nosso trabalho:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)![numpy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)![matplotlib](https://img.shields.io/badge/matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)![seaborn](https://img.shields.io/badge/seaborn-4DB6AC?style=for-the-badge&logo=seaborn&logoColor=white)![plotly](https://img.shields.io/badge/plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)![Canvas](https://img.shields.io/badge/Canvas-FF914D?style=for-the-badge&logo=canvas&logoColor=black)![API](https://img.shields.io/badge/API-4D4D4D?style=for-the-badge&logo=api&logoColor=white)![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)![CSV](https://img.shields.io/badge/CSV-007ACC?style=for-the-badge&logo=file&logoColor=white)![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)![ZIP](https://img.shields.io/badge/ZIP-4D4D4D?style=for-the-badge&logo=zip&logoColor=white)

Essas tecnologias e ferramentas desempenharam papéis complementares em nossa análise, permitindo-nos conduzir uma análise exploratória abrangente e comunicar nossos insights de forma eficaz.

---

## <center> <font color='bluegreen'> **Guia de Utilização** </font> </center>

Siga as instruções abaixo para obter insights valiosos a partir dos arquivos fornecidos.

### Pasta "Arquivos_Análise" (Arquivos e Conjunto de Dados):

A pasta "Arquivos_Análise" contém os recursos utilizados na construção da análise de criptomoedas. Você encontrará os arquivos necessários para explorar a análise de dados das séries históricas de criptomoedas. Certifique-se de clonar ou baixar essa pasta para sua máquina e mantê-la na mesma localização do projeto.

- **Arquivo "Análise_Cripto.ipynb"**: Este arquivo contém o relatório completo da análise de criptomoedas, incluindo respostas, visualizações e insights. Você pode acessá-lo [aqui](https://github.com/luhonunes/Criptomoedas_Resilia/blob/main/Arquivos_An%C3%A1lise/An%C3%A1lise_Cripto.ipynb).

- **Arquivo "Preparação_Cripto.ipynb"**: Este arquivo contém instruções detalhadas do processo ETL, desde a importação dos dados no Google Colab até a obtenção do arquivo CSV tratado, a importação desse arquivo para o banco de dados PostgreSQL via PgAdmin e a interação do banco de dados com o Power BI. Você pode acessá-lo [aqui](https://github.com/luhonunes/Criptomoedas_Resilia/blob/main/Arquivos_An%C3%A1lise/Prepara%C3%A7%C3%A3o_Cripto.ipynb).

### Pasta "Arquivos_Power_BI" (Relatórios do Power BI):

A pasta "Arquivos_Power_BI" contém o arquivo ".pbix" do Power BI, que permite a visualização interativa dos resultados da análise de criptomoedas. Certifique-se de clonar ou baixar essa pasta para sua máquina e mantê-la na mesma localização do projeto.

### Pasta "Dados_Cripto" (Conjuntos de Dados):

A pasta "Dados_Cripto" contém os arquivos CSV das 10 criptomoedas escolhidas para análise. Esses arquivos são fundamentais para realizar a análise exploratória. Você pode acessar esses arquivos diretamente na pasta.

### Pasta "Imagens_Candlestick" (Visualizações de Candlestick):

A pasta "Imagens_Candlestick" contém as imagens no formato PNG das visualizações estáticas dos gráficos de candlestick gerados com o Plotly. Essas imagens podem ser úteis para referência visual.

### Pasta "Imagens_Instruções" (Imagens do Tutorial):

A pasta "Imagens_Instruções" contém imagens utilizadas no arquivo "Preparação_Cripto.ipynb" para ilustrar o tutorial detalhado do processo ETL.

### Pasta "Imagens_Relatório" (Imagens do Relatório do Power BI):

A pasta "Imagens_Relatório" contém imagens geradas pelas visualizações interativas no Power BI, que são parte integrante do relatório final.

### Pasta "Slide" (Apresentação do Projeto):

A pasta "Slide" contém a apresentação do projeto, gerada no Canvas e salva em formato PDF.

Utilize esses recursos e pastas conforme necessário para explorar, compreender e comunicar os resultados da análise de criptomoedas. Os arquivos e pastas estão organizados para facilitar a navegação e o entendimento de todo o projeto.

### Configurações Necessárias:

Antes de prosseguir, certifique-se de que você tenha as seguintes configurações em seu ambiente:

- **Bibliotecas Python:** Verifique se você instalou todas as bibliotecas Python necessárias para executar os notebooks, como pandas, numpy, matplotlib, plotly, entre outras. Você pode instalar essas bibliotecas usando o comando pip install nome_da_biblioteca.

- **Power BI:** Certifique-se de que você tenha o Power BI Desktop instalado em sua máquina, se você pretende abrir e interagir com os relatórios do Power BI. Você pode baixar o Power BI Desktop no site oficial da Microsoft.

- **Banco de Dados:** Se você está interagindo com um banco de dados PostgreSQL via PgAdmin, verifique se o PostgreSQL está instalado e configurado corretamente em sua máquina. Além disso, certifique-se de que o PgAdmin esteja configurado para se conectar ao PostgreSQL.

- **Arquivos de Dados:** Verifique se você tem os arquivos de dados necessários (CSVs) disponíveis no local esperado para a análise.

- **Conta Google:** Se você estiver usando o Google Colab, certifique-se de estar conectado à sua conta do Google para acessar os notebooks.

- **Chaves de API:** Se você estiver acessando APIs externas, como para obter dados de criptomoedas em tempo real, verifique se você possui as chaves de API necessárias e as configurações de segurança apropriadas.

- **Ambiente Virtual (Opcional):** Para isolar as dependências do projeto, você pode considerar o uso de ambientes virtuais Python, como o virtualenv ou o conda, para garantir que as bibliotecas e versões corretas sejam usadas para o projeto.

### Bibliotecas Utilizadas:

As seguintes bibliotecas foram utilizadas neste projeto para análise e visualização de dados:

            pandas as pd
            matplotlib.pyplot as plt
            matplotlib.ticker as ticker
            seaborn as sns
            zipfile as zp
            google.colab files
            os
            import plotly.graph_objects as go
            numpy as np

Certas bibliotecas serão necessárias para executar os códigos. Você pode instalá-las utilizando o comando pip install nome_da_biblioteca.
Certifique-se de ter essas bibliotecas instaladas para evitar problemas de execução.


Aproveite ao máximo esta análise de dados das séries históricas de Criptomoedas. Sinta-se à vontade para explorar, executar os códigos e extrair insights relevantes para suas análises. Se tiver alguma dúvida, consulte a documentação das bibliotecas mencionadas.

---

## <center> <font color='bluegreen'> **Considerações Finais** </font> </center>

À medida que você se prepara para explorar a análise de criptomoedas e aproveitar os recursos disponíveis neste repositório, aqui estão algumas considerações finais que podem ajudá-lo a obter o máximo proveito deste projeto:

- **Exploração Criativa**: Sinta-se à vontade para explorar e analisar os dados de criptomoedas de maneira criativa. Experimente diferentes visualizações e abordagens para descobrir insights únicos.

- **Colaboração**: Este projeto é fruto do trabalho árduo e da colaboração de várias pessoas. Agradecemos a todos os colaboradores e membros da comunidade que contribuíram para tornar este projeto possível.

- **Referências Adicionais**: Se você deseja aprender mais sobre análise de criptomoedas, análise de dados ou outras áreas relacionadas, considere verificar recursos adicionais, como cursos online, tutoriais e comunidades online.

---

## <center> <font color = 'bluegreen'> **Feedback e Melhorias** </font> </center> 

Se você tiver feedback, sugestões de melhorias ou encontrar problemas nos notebooks ou recursos, fique à vontade para compartilhá-los. A melhoria contínua é fundamental.

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue neste repositório.

Aproveite ao máximo este projeto e as informações disponíveis. Desejamos a você uma jornada de análise de dados bem-sucedida e enriquecedora.

Com gratidão,

Equipe.

<center><img src="https://github.com/luhonunes/Criptomoedas_Resilia/blob/main/Imagens_Relat%C3%B3rio/Logo.png?raw=true"></center>


---
