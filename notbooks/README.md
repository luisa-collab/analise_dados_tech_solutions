
# Análise de Dados de Funcionários e Benefícios

## 📊 Análise de Dados de Funcionários e Benefícios

Este projeto apresenta uma **análise fictícia** da saúde organizacional da empresa Tech Solutions Ltda, com foco em Recursos Humanos. Ele explora dados de funcionários e seus benefícios, utilizando Python para processamento, limpeza e visualização das informações, permitindo insights sobre salários, satisfação e distribuição de benefícios.

## 🔻 Estrutura do Projeto

├── data/
│ ├── funcionarios.csv
│ └── beneficios.csv
├── visualizations/
│ ├── salarios_por_cargo.png
│ └── satisfacao_funcionarios.png
├── analysis.py
└── README.md

## 🔎 Etapas da Análise

1. **Importação de bibliotecas**:  `PANDAS`, `MATPLOTLIB`, `SEABORN`.

2. **Carregamento e limpeza de dados**: Leitura dos CSVs com encoding correto, remoção de espaços e normalização de colunas.

3.**Tradução e padronização das colunas**:
-Exemplo: `Salário (r$)` → `Salario`, `Satisfação(%)` → `Satisfacao`.

4.**Visualização e análise exploratória**: Gráficos de salários por cargo e distribuição de satisfação

5.**Insights e conclusões**: Interpretação dos resultados.

## 📑 Amostra dos Dados

### Funcionários

| ID | Nome           | Cargo                     | Salario | Tempo (anos) | Satisfacao |
|----|----------------|--------------------------|--------|--------------|------------|
| 1  | Ana Silva      | Gerente de Vendas        | 4500   | 5            | 85         |
| 2  | Bruno Costa    | Analista de Marketing    | 6200   | 3            | 90         |
| 3  | Carla Souza    | Desenvolvedora de Software| 8000   | 4           | 95         |
| 4  | Daniel Lima    | Designer Gráfico         | 2900   | 2            | 80         |
| 5  | Elisa Fernandes| Coordenadora de Projetos | 7200   | 6            | 88         |

### Benefícios

| Tipo de Benefício | Descricao                 | Taxa de Adesao | Valor Fixo |
|------------------|---------------------------|----------------|------------|
| Plano de Saúde    | Cobertura médica completa | 90             | -          |
| Vale-Alimentação  | R$ 500 por mês           | 100            | -          |
| Vale-Transporte   | R$ 300 por mês           | 85             | -          |
| Seguro de Vida    | Cobertura Básica          | 70             | -          |
| Bônus Anual       | Baseado em desempenho    | 60             | -          |

---
1️⃣ Salários por Cargo

![Salários por Cargo](visualizations/salarios_por_cargo.png)

### 2️⃣ Distribuição de Satisfação dos Funcionários

![Satisfação](visualizations/satisfacao_funcionarios.png)

---

## 💡 Insights Fictícios

- Os cargos mais altos apresentam **salários mais elevados**.  
- A maioria dos funcionários apresenta **satisfação acima de 80%**.  
- Benefícios com maior taxa de adesão podem **impactar positivamente a retenção e satisfação**.  

---

## ⚙️ Tecnologias Utilizadas

- **Python 3.11**  
- **Pandas** → manipulação de dados  
- **Matplotlib e Seaborn** → visualização de dados  

---

## 🚀 Como Rodar o Projeto

1.Clone o repositório:
```bash
git clone https://github.com/luisa-collab/analise-funcionarios.git