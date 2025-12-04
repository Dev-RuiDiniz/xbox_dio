# 📊 Dashboard de Vendas Xbox Game Pass - DIO

Este projeto consiste na criação de um **Dashboard de Vendas** no **Microsoft Excel**, desenvolvido como parte de um desafio prático da plataforma DIO. O objetivo principal é transformar dados brutos de assinaturas do Xbox Game Pass em informações visuais claras e úteis, facilitando a **análise de desempenho de vendas** e o **processo de tomada de decisão** baseada em dados.

---

## 🎯 Objetivo do Projeto

O desafio visa aplicar habilidades de organização de dados, visualização e criação de *dashboards* para:

1.  **Organizar e Estruturar** um conjunto de dados brutos de vendas.
2.  **Visualizar** as principais métricas de vendas de forma clara e interativa.
3.  Permitir uma **Análise Eficaz** do desempenho de vendas das diferentes categorias de assinaturas e seus adicionais.

---

## 📁 Estrutura de Arquivos e Dados

O projeto é centralizado no arquivo Excel, que contém as seguintes abas/bases de dados:

| Arquivo/Aba | Descrição |
| :--- | :--- |
| `Bases` (`xbox_dio.xlsx` / `base_dados.xlsx`) | Contém a **base de dados bruta** das assinaturas, incluindo informações como ID do Assinante, Plano (*Core, Standard, Ultimate*), Preço, Tipo de Assinatura (*Mensal, Trimestral, Anual*), e adicionais (*EA Play, Minecraft Season Pass*). |
| `Cálculos` | Aba dedicada para a criação das **Tabelas e Gráficos Dinâmicos** e fórmulas auxiliares que alimentam o *Dashboard*. |
| `Assets` | Contém recursos de design, como a paleta de cores e logotipos, utilizados para manter a identidade visual do Xbox no *Dashboard*. |
| `Dashboard` | A **visualização final** e interativa, apresentando os principais indicadores de desempenho (KPIs) de vendas de forma consolidada. |

### Dados Utilizados (Visão Geral)

A base de dados de assinaturas inclui colunas como:

* `Plan`: Categoria do plano (Core, Standard, Ultimate).
* `Subscription Type`: Frequência do pagamento (Monthly, Quarterly, Annual).
* `Total Value`: Receita total gerada pela assinatura.
* `Auto Renewal`: Indica se a renovação é automática.
* `EA Play Season Pass Price` / `Minecraft Season Pass Price`: Valor dos adicionais.

---

## 📈 Principais Análises e Métricas

O Dashboard foi construído para responder a perguntas de negócio cruciais, como:

* **Faturamento Total** por Tipo de Plano (Core, Standard, Ultimate).
* **Faturamento Total** de planos anuais, separado por assinaturas com e sem **Auto Renovação**.
* **Total de Vendas** dos adicionais (*EA Play Season Pass* e *Minecraft Season Pass*).
* Desempenho de vendas por **Tipo de Assinatura** (Mensal, Trimestral, Anual).

---

## 🛠️ Instruções para Reprodução

Para visualizar e analisar o *Dashboard*, siga os passos abaixo:

1.  **Clone o Repositório:**
    ```bash
    git clone <(https://github.com/Dev-RuiDiniz/xbox_dio)>
    ```
2.  **Abra o Arquivo:**
    Localize e abra o arquivo `xbox_dio.xlsx` (ou `base_dados.xlsx`) no **Microsoft Excel** (versão recomendada: 2013 ou superior) ou em um software compatível.
3.  **Explore o Dashboard:**
    Navegue até a aba **`Dashboard`** para interagir com a visualização. Utilize os **segmentadores de dados** (Slicers) para filtrar as informações por Plano, Tipo de Assinatura e outras variáveis.
4.  **Verifique os Cálculos:**
    A aba **`Cálculos`** contém todas as Tabelas Dinâmicas e as fórmulas utilizadas para gerar os KPIs e os gráficos apresentados.

---

## ✒️ Autor

**RUI FRANCISCO DE PAULA INÁCIO DINIZ**
