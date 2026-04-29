# PBL-Fase-3-Banco-de-Dados-Oracle-FarmTech-Solutions
integrantes:
Gustavo Henrique de Andrade - RM564102

Descrição do Projeto
Este projeto foi desenvolvido como parte da Fase 3 do PBL (Project-Based Learning) do curso de Inteligência Artificial da FIAP.
O objetivo desta etapa foi realizar a importação de dados de sensores agrícolas para um banco de dados relacional Oracle, utilizando o Oracle SQL Developer, permitindo o armazenamento e a consulta estruturada das informações coletadas.
A proposta simula um cenário da startup fictícia FarmTech Solutions, que atua com soluções inteligentes para o agronegócio.
Como o arquivo original da Fase 2 não estava disponível no momento do desenvolvimento, foi utilizada uma base simulada em formato CSV com dados compatíveis com sensores agrícolas, mantendo a proposta técnica da atividade.

Objetivo
Importar uma base de dados de sensores agrícolas para o Oracle Database utilizando o Oracle SQL Developer, criar uma tabela relacional e realizar consultas SQL para validação dos dados importados.

Estrutura do Projeto
fase3/
README.md
dados/sensores_agro.csv
prints/csv.png
prints/importacao.png
prints/tabela.png
prints/select.png

Base de Dados Utilizada
A base utilizada foi um arquivo CSV contendo dados simulados de sensores agrícolas com as seguintes variáveis:


id_sensor


umidade


ph


fosforo


potassio


irrigacao


A base representa informações coletadas por sensores agrícolas para monitoramento de condições do solo e apoio à tomada de decisão em sistemas inteligentes de irrigação.

Etapas Realizadas
1. Criação da base CSV
Foi criada uma base em formato CSV contendo dados simulados de sensores agrícolas para representar os dados da Fase 2.
2. Importação no Oracle SQL Developer
A base sensores_agro.csv foi importada para o Oracle SQL Developer utilizando o assistente de importação de dados.
Durante a importação, foi criada a tabela SENSORES_AGRO.
3. Validação da Importação
Após a importação, foi realizada uma consulta SQL para validar a carga dos dados no banco.
Consulta executada:
SELECT * FROM SENSORES_AGRO;

Evidências (Prints)
Base CSV criada
(Adicionar print: prints/csv.png)
Importação no Oracle SQL Developer
(Adicionar print: prints/importacao.png)
Tabela criada no Oracle
(Adicionar print: prints/tabela.png)
Consulta SQL executada
(Adicionar print: prints/select.png)

Resultado
Os dados foram importados com sucesso para o banco Oracle e armazenados em uma tabela relacional, permitindo consultas SQL para exploração e validação das informações.
A atividade demonstrou com sucesso o processo de carga, estruturação e consulta de dados em banco relacional, aplicando conceitos iniciais de banco de dados no contexto do agronegócio.

Tecnologias Utilizadas


Oracle SQL Developer


Oracle Database


Microsoft Excel


GitHub



Vídeo Demonstrativo
Link do vídeo no YouTube (não listado):
(Adicionar link do vídeo aqui)

Conclusão
A atividade permitiu aplicar na prática conceitos de banco de dados relacionais, importação de dados e consultas SQL, demonstrando a importância da organização e persistência de dados em projetos de Inteligência Artificial aplicados ao agronegócio.
