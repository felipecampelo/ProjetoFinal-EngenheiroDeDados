# Projeto Final - Engenheiro de Dados

Esse foi o Workflow do nosso projeto de ETL, onde utilizamos, no total, 7 datasets, sendo eles em formatos distintos como XLS, CSV, XLSX e diretamente de um banco de dados. Os dados brutos foram armazenados no Google Cloud Storage e no MySQL. O tratamento foi realizado no Google Colab com o uso das ferramentas PySpark e Pandas. Após o tratamento, foi criada uma pipeline com o Apache Beam para o envio direto para o Google Cloud Storage e, via conector, os dados tratados foram enviados para o BigQuery. Via modelo pré-definido do Google Dataflow, realizamos o envio dos dados tratados do BigQuery para o MongoDB e, por fim, inserimos os dados no Google DataStudio para análise dos dados.

<img src="C:\Users\felip\Downloads\Prints Projeto Final"/>
