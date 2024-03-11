Bootcamp de preparação para a certificação AI-900 da Microsoft.

Nossa primeira prática foi a realização de um laboratório inicial proposto pela própria plataforma Azure, claro com a ajuda da Professora expert no assunto!

1 – Acessando o serviço do Azure Machine-Learning:

Primeiro temos que criar uma conta no AZURE para iniciar o acompanhamento com a professora.
Em seguida pesquisamos por “Azure Machine Learning” para criar uma instância para o laboratório, clicar em “create” para iniciar as configurações, só seguir o passo a passo da Professora que vai dar bom! 



2 – Configurando Modelos e Conjuntos de Dados:

Agora vamos configurar o modelo e conjunto de dados para teste, seguindo as instruções do laboratório como no passo anterior.

3 - Análise e teste do modelo:

Na aba "Métricas" vamos analisar os gráficos dos dados gerados pelo modelo.
Em "Pontos de Extremidade" ou "Endpoints" vamos coloar o seguinte código e testar:

 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }

_________________________________________________________________________________________________________________________________________________

Laboratório 2 =>




