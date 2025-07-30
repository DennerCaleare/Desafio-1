# 📊 Análise de Churn de Clientes - TelecomX Brasil

Este projeto foi desenvolvido como parte de um desafio da Alura, focado na análise de dados de churn de clientes para a empresa fictícia TelecomX Brasil. O objetivo principal é identificar padrões e fatores que contribuem para o cancelamento de serviços, fornecendo insights acionáveis para estratégias de retenção.

## 🚀 Como Rodar o Projeto

Para executar este notebook e replicar a análise, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd <NOME_DO_SEU_REPOSITORIO>
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3.  **Instale as dependências:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

4.  **Baixe os dados:**
    Certifique-se de que o arquivo `TelecomX_Data.json` esteja na mesma pasta do notebook `TelecomX_BR_FINAL_CORRIGIDO.ipynb`.

5.  **Abra o notebook Jupyter:**
    ```bash
    jupyter notebook TelecomX_BR_FINAL_CORRIGIDO.ipynb
    ```
    Se você não tiver o Jupyter instalado, pode instalá-lo com `pip install notebook`.

6.  **Execute as células:**
    Execute todas as células do notebook sequencialmente para ver a análise completa, incluindo a extração, transformação, análise exploratória de dados, gráficos e o relatório final.

## 🔍 Principais Insights

Com base na análise realizada no notebook, as seguintes descobertas são destacadas:

*   **Taxa de Churn:** A taxa geral de churn foi de aproximadamente **26.5%**, indicando um desafio significativo na retenção de clientes.
*   **Contratos:** Clientes com contratos **mês-a-mês** apresentam uma taxa de churn significativamente maior (cerca de **42.7%**) em comparação com contratos de um ano (11.3%) e dois anos (2.9%). Isso sugere que contratos de longo prazo são um forte indicador de retenção.
*   **Serviços de Internet:** Clientes com serviço de **Fibra Óptica** têm uma taxa de churn mais alta (cerca de **41.9%**) do que aqueles com DSL (19.0%) ou sem serviço de internet (7.4%). Isso pode indicar problemas de qualidade ou satisfação com o serviço de fibra.
*   **Tempo de Permanência (Tenure):** Clientes que cancelam tendem a ter um tempo de permanência médio muito menor (cerca de **18 meses**) em comparação com clientes que permanecem (cerca de **38 meses**). Clientes nos primeiros meses são mais propensos a cancelar.
*   **Demografia:** Clientes **idosos (SeniorCitizen)** apresentam uma taxa de churn mais elevada (cerca de **41.7%**) do que os não-idosos (23.9%). Além disso, clientes **sem parceiro** também mostram maior propensão ao churn (33.0%) do que aqueles com parceiro (20.0%).
*   **Encargos Mensais:** Clientes com encargos mensais mais altos, especialmente aqueles com serviços de internet e streaming, tendem a ter uma taxa de churn maior.

## 💡 Recomendações Estratégicas

Para mitigar o churn, as seguintes recomendações são propostas:

1.  **Incentivar Contratos de Longo Prazo:** Oferecer descontos e benefícios para clientes que optam por contratos anuais ou bienais.
2.  **Melhorar a Qualidade da Fibra Óptica:** Investigar e resolver problemas de serviço para clientes de fibra, talvez com suporte técnico proativo.
3.  **Programas de Retenção para Grupos de Risco:** Desenvolver campanhas direcionadas para clientes idosos, clientes sem parceiro e aqueles nos primeiros meses de serviço.
4.  **Revisar Estratégia de Preços:** Avaliar a competitividade dos preços, especialmente para pacotes com múltiplos serviços.

## 👤 Autor

Desenvolvido por **Denner Caleare** para o desafio de dados da Alura.

---

