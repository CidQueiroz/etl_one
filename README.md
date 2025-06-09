# Projeto ETL - Análise de Evasão de Clientes (Churn) da TelecomX

Este projeto tem como objetivo realizar um processo completo de **ETL (Extração, Transformação e Carga)** e análise exploratória dos dados de clientes da empresa fictícia **TelecomX**, visando identificar os principais fatores que contribuem para a evasão de clientes (churn) e propor recomendações estratégicas para retenção.

## 📁 Estrutura do Projeto

- **TelecomX_BR.ipynb**: Notebook principal contendo todo o fluxo de ETL, análise exploratória e relatório final.
- **Outros arquivos**: Notebooks e datasets auxiliares para estudos e testes.

## 🚀 Como Executar

1. **Pré-requisitos**  
   Certifique-se de ter o Python 3.x instalado e as seguintes bibliotecas:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - requests

   Instale as dependências com:
   ```bash
   pip install pandas numpy matplotlib seaborn requests

2. **Execução**
    - Abra o arquivo TelecomX_BR.ipynb em um ambiente Jupyter Notebook (VS Code, JupyterLab, etc.) e execute as células sequencialmente.

## 📊 Fluxo do Notebook TelecomX_BR.ipynb
    **Extração**

   - Os dados são extraídos de uma API pública (JSON hospedado no GitHub).
   - Utiliza as bibliotecas requests e pandas para carregar os dados em um DataFrame.

    **Transformação**

   - Padronização dos nomes das colunas.
   - Remoção de linhas inconsistentes e tratamento de valores nulos.
   - Conversão de colunas para tipos adequados e preenchimento de valores ausentes com a mediana ou moda.

    **Carga e Análise**

   - Análise exploratória dos dados (EDA) com visualizações usando matplotlib e seaborn.
   - Geração de estatísticas descritivas, gráficos de distribuição, correlação e detecção de outliers.

    **Relatório Final**

   - Apresentação dos principais insights sobre o churn.
   - Recomendações estratégicas para redução da evasão de clientes.

## 📈 Principais Insights
   - Contratos mensais, uso de fibra óptica e pagamento via cheque eletrônico estão fortemente associados ao churn.
   - Clientes com menor tempo de permanência e cobranças mensais mais altas têm maior risco de evasão.

## 📝 Recomendações
   - Incentivar migração para contratos mais longos.
   - Investigar a satisfação dos clientes de fibra óptica.
   - Otimizar métodos de pagamento, promovendo opções automáticas.
   - Monitorar clientes novos e com cobranças elevadas para ações proativas de retenção.

## 📚 Referências
   - Desafio Data Science - Alura
   - Documentação das bibliotecas: pandas, matplotlib, seaborn
   - Projeto desenvolvido para fins educacionais no contexto do curso de Data Science e Inteligência Artificial. ```
