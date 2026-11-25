![Header](https://capsule-render.vercel.app/api?type=waving&height=300&color=gradient&section=header&reversal=false&text=An%C3%A1lise+com+Python&textBg=false&fontSize=76&fontAlign=50&fontAlignY=43&animation=fadeIn&rotate=0&strokeWidth=0&desc=An%C3%A1lise+Explorat%C3%B3ria+de+Dados+de+Vendas+com+Pandas&descSize=30&descAlign=50&descAlignY=64)

<div align="center">
  <!-- Badges / Shields.io -->
  <a href="#">
    <img src="https://img.shields.io/badge/Python-3.10+-18181b?style=for-the-badge&logo=python&logoColor=10b981" alt="Python Version" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Pandas-2.0+-18181b?style=for-the-badge&logo=pandas&logoColor=10b981" alt="Pandas Version" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Concluído-10b981?style=for-the-badge&labelColor=18181b" alt="Project Status" />
  </a>

  <br />
  <sub>Desenvolvido como parte do monorepo de projetos analíticos <a href="https://github.com/castroluizes/Py-Analise"><b>Py-Analise</b></a>.</sub>
</div>

---

> [!NOTE]
> **Status do Projeto:** 🟡 Em Andamento | **Tecnologias:** Python, Pandas, NumPy, Seaborn, Matplotlib, Plotly


## Análise Exploratória de Dados de Vendas com Pandas

---

### 🌿 Visão Geral do Projeto

Em operações de e-commerce em expansão, dados brutos raramente chegam prontos para análise. Inconsistências de tipo, registros duplicados, valores ausentes e *outliers* na precificação ou frete podem distorcer indicadores financeiros fundamentais.

Este projeto simula e resolve esse cenário real: constrói um pipeline completo de tratamento de dados transacionais usando **Python** e **Pandas**, transformando registros brutos em uma base limpa, enriquecida com métricas de negócio e pronta para tomada de decisão estratégica.

#### 🎯 Principais Respostas de Negócio
- **Desempenho Comercial:** Faturamento total, ticket médio e sazonalidade de vendas diárias.
- **Mix de Produtos:** Categorias mais rentáveis e itens com maior volume de saída.
- **Eficiência Operacional:** Distribuição do *status* de entrega e gargalos de logística.

---

### 🛠️ Tecnologias e Ferramentas

| Categoria | Tecnologia | Aplicação |
| :--- | :--- | :--- |
| **Linguagem** | `Python 3.10+` | Processamento de scripts e análise vetorial |
| **Tratamento de Dados** | `Pandas` / `NumPy` | Limpeza, conversão de tipos, imputação e feature engineering |
| **Visualização Estática** | `Matplotlib` / `Seaborn` | Gráficos exploratórios e distribuições estatísticas |
| **Visualização Interativa** | `Plotly` | Dashboards dinâmicos para análise de tendência diária |

---

### 🔄 Etapas do Pipeline de Dados

```text
  [ Dados Brutos ] ──► ( 1. Limpeza & Tratamento ) ──► ( 2. Feature Engineering ) ──► [ Dataset Validador ]
                                                                                            │
  [ Relatório Final ] ◄── ( 4. Síntese de Negócio ) ◄── ( 3. EDA & Visualização ) ◄────────┘
