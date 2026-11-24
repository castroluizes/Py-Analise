<div align="center">

  <!-- Banner SVG Integrado (Sem dependências externas) -->
  <svg viewBox="0 0 800 200" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="200" rx="12" fill="#18181b"/>
    <!-- Detalhe decorativo minimalista -->
    <circle cx="720" cy="40" r="120" fill="#10b981" opacity="0.08"/>
    <circle cx="760" cy="160" r="80" fill="#059669" opacity="0.12"/>
    <path d="M 50 140 L 120 110 L 190 125 L 260 80 L 330 95 L 400 50" fill="none" stroke="#10b981" stroke-width="4" stroke-linecap="round" opacity="0.8"/>
    <circle cx="400" cy="50" r="5" fill="#34d399"/>
    
    <!-- Texto do Banner -->
    <text x="50" y="85" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica" font-size="28" font-weight="700" fill="#ffffff" letter-spacing="-0.5">E-Commerce Data Pipeline</text>
    <text x="50" y="115" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica" font-size="14" font-weight="400" fill="#a1a1aa">Limpeza, Engenharia de Atributos e EDA Transacional com Pandas</text>
  </svg>

  <br />

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
  <br />

  <sub>Desenvolvido como parte do monorepo de projetos analíticos <a href="https://github.com/castroluizes/Py-Analise"><b>Py-Analise</b></a>.</sub>

</div>

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