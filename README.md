# Análise de Bancos que falharam nos EUA

Projeto realizado para estudar análise de dados / Power BI.
O Dataset utilizado pode ser acessado aqui: https://catalog.data.gov/dataset/fdic-failed-bank-list

Este repositório contém o arquivo com o modelo para importação no Power BI e um PDF com a visualização do Dashboard Final.

Etapas:

**Transformação de Dados**
  - Remoção de colunas
  - Merge de colunas por exemplo
    
**Modelagem de Dados**
  - Criação de tabela de datas com DAX (Função CALENDARAUTO e extração de mês e ano para outras colunas)
  - Relação 1 para Muitos entre Data e Banco que Falhou

**Visualização**
-Criação dos gráficos para visualização de:
  - Estados dos EUA onde mais bancos falharam
  - Contagem de bancos que falharam por mês
  - Segmentação de dados por período em anos.
